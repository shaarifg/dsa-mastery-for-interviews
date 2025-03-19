Here’s your **`stringbuilder.md`** file, structured exactly as per your **GitHub DSA format**. 🚀

---

## **📌 StringBuilder - Concepts, Patterns & LeetCode Problems**

---

## **📍 1. What is StringBuilder?**

`StringBuilder` is a **mutable sequence of characters**, meaning it allows **modifications without creating new objects** (unlike `String`, which is immutable).

**💡 Why Use StringBuilder?**  
✔ **Efficient for String Manipulation** (Appending, Reversing, Inserting).  
✔ **Better Performance than `String` for Repeated Modifications**.  
✔ **Reduces Memory Usage** (Avoids unnecessary object creation).

**🚀 Key Use Cases:**  
🔹 **Concatenating multiple strings efficiently.**  
🔹 **Reversing a string in O(n) time.**  
🔹 **Modifying a large string without performance loss.**

---

## **📍 2. StringBuilder vs String - Performance Comparison**

| **Operation**                    | **`String` (Immutable - Creates New Object)** | **`StringBuilder` (Mutable - Modifies in Place)** |
| -------------------------------- | --------------------------------------------- | ------------------------------------------------- |
| **Concatenation (`+` Operator)** | Slow (O(n²) due to new object creation)       | Fast (O(n))                                       |
| **Modification (Insert/Delete)** | Not Possible                                  | Efficient                                         |
| **Reversing a String**           | Requires extra space (O(n))                   | In-place (O(n))                                   |
| **Memory Usage**                 | High                                          | Low                                               |

---

## **📍 3. Important Methods in StringBuilder**

```java
// ✅ DECLARATION & INITIALIZATION
StringBuilder sb = new StringBuilder("Hello");

// ✅ APPEND STRING
sb.append(" World");  // "Hello World"

// ✅ INSERT AT SPECIFIC INDEX
sb.insert(5, " Beautiful");  // "Hello Beautiful World"

// ✅ DELETE CHARACTERS
sb.delete(5, 15);  // Removes " Beautiful", Result: "Hello World"

// ✅ REPLACE CHARACTERS
sb.replace(6, 11, "Java");  // "Hello Java"

// ✅ REVERSE STRING
sb.reverse();  // "avaJ olleH"

// ✅ GET CHARACTER AT INDEX
char ch = sb.charAt(4);  // 'o'

// ✅ CONVERT TO STRING
String str = sb.toString();  // Converts to normal String

// ✅ GET LENGTH OF STRINGBUILDER
int length = sb.length();

// ✅ SET CHARACTER AT INDEX
sb.setCharAt(0, 'h');  // Change 'H' -> 'h'

// ✅ TRIM CAPACITY (Reduce Memory Usage)
sb.trimToSize();

// ✅ ENSURE CAPACITY (Optimize Performance)
sb.ensureCapacity(50);
```

---

## **📍 4. Common Patterns & Use Cases**

| **Pattern**                                   | **When to Use?**                                         | **Complexity** |
| --------------------------------------------- | -------------------------------------------------------- | -------------- |
| **Concatenation of Large Strings**            | Use `StringBuilder` instead of `+` operator.             | **O(n)**       |
| **Reversing a String Efficiently**            | Use `sb.reverse()` instead of manual iteration.          | **O(n)**       |
| **Building Dynamic Strings in Loops**         | When modifying strings multiple times.                   | **O(n)**       |
| **Processing Large Text Data**                | For operations like `append()`, `replace()`, `insert()`. | **O(n)**       |
| **Efficiently Generating Strings for Output** | `StringBuilder` avoids unnecessary object creation.      | **O(n)**       |

---

## **📍 5. LeetCode Questions That Require StringBuilder**

| **Category**                           | **LeetCode Problems**  |
| -------------------------------------- | ---------------------- |
| **Reverse String & Modify In-Place**   | **344, 151, 917, 541** |
| **String Compression & Decompression** | **443, 271, 604**      |
| **Build String Efficiently**           | **415, 67, 989, 482**  |
| **Modify & Remove Characters**         | **227, 8, 394, 71**    |

---

## **📍 6. Best Practices**

✔ **Always use `StringBuilder` for multiple modifications instead of `String`**.  
✔ **Use `.reverse()` instead of writing custom reverse logic**.  
✔ **Use `.setCharAt()` for modifying a single character instead of creating a new string**.  
✔ **Prefer `StringBuilder` for string operations inside loops (avoids O(n²) complexity).**  
✔ **Use `.toString()` only when final conversion is needed to avoid unnecessary object creation.**

---
