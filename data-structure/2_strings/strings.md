# 📌 Strings - Concepts, Patterns & Problem-Solving Guide

🔥 **Everything you need for mastering Strings in interviews!**  
✅ **Concepts & Explanations**  
✅ **Common Patterns & Use Cases**  
✅ **LeetCode Questions List**  
✅ **Time Complexity Analysis**  
✅ **Best Practices**

---

## **📌 1. String Basics & Key Operations**

### **🔹 String Declaration & Immutability**

```java
String s1 = "hello";  // String literal (stored in String Pool)
String s2 = new String("hello");  // Stored in Heap memory


// ✅ Get Length
int len = s.length();

// ✅ Character Access
char first = s.charAt(0);

// ✅ Substring Extraction
String sub = s.substring(2, 5);  // s[2:5]

// ✅ Convert to Array
char[] charArray = s.toCharArray();

// ✅ Convert to Lower/Upper Case
String lower = s.toLowerCase();
String upper = s.toUpperCase();

// ✅ Check if String Contains Another String
boolean exists = s.contains("hello");

// ✅ Replace Characters
String newString = s.replace("a", "b");

// ✅ Remove Whitespaces
String trimmed = s.trim();

// ✅ Split a String
String[] words = s.split(" ");

// ✅ Join an Array of Strings
String joined = String.join("-", words);

📌 2. Key Techniques & Patterns
Pattern	When to Use	Time Complexity
Two Pointers	Reverse, Palindrome Check	O(n)
Sliding Window	Longest Substring Without Repeating Characters	O(n)
Prefix Hashing	Count substring occurrences efficiently	O(n)
KMP Algorithm (Pattern Matching)	Fast substring search	O(n+m)
Z Algorithm	Pattern Matching	O(n+m)
Rabin-Karp Algorithm	Substring Matching (Rolling Hash)	O(n+m)
Manacher’s Algorithm	Find Longest Palindromic Substring	O(n)
Trie (Prefix Tree)	Auto-complete, Dictionary Matching	O(n)


Category	LeetCode Problems
Basic String Operations	344, 14, 28, 387
Two Pointers	125, 392, 151, 345
Sliding Window	3, 76, 567, 424
Pattern Matching	28, 214, 139, 140
Palindromes	5, 9, 266, 647
Sorting & Grouping	49, 242, 937, 791
```
