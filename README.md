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


---

## 📌 2. Key Techniques & Patterns

| **Pattern** | **When to Use** | **Time Complexity** |
|------------|----------------|----------------------|
| **Two Pointers** | Reverse, Palindrome Check | **O(n)** |
| **Sliding Window** | Longest Substring Without Repeating Characters | **O(n)** |
| **Prefix Hashing** | Count substring occurrences efficiently | **O(n)** |
| **KMP Algorithm (Pattern Matching)** | Fast substring search | **O(n+m)** |
| **Z Algorithm** | Pattern Matching | **O(n+m)** |
| **Rabin-Karp Algorithm** | Substring Matching (Rolling Hash) | **O(n+m)** |
| **Manacher’s Algorithm** | Find Longest Palindromic Substring | **O(n)** |
| **Trie (Prefix Tree)** | Auto-complete, Dictionary Matching | **O(n)** |

---

## 📌 LeetCode Questions for Strings

| **Category** | **LeetCode Problems** |
|------------|----------------|
| **Basic String Operations** | [344](https://leetcode.com/problems/reverse-string/), [14](https://leetcode.com/problems/longest-common-prefix/), [28](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/), [387](https://leetcode.com/problems/first-unique-character-in-a-string/) |
| **Two Pointers** | [125](https://leetcode.com/problems/valid-palindrome/), [392](https://leetcode.com/problems/is-subsequence/), [151](https://leetcode.com/problems/reverse-words-in-a-string/), [345](https://leetcode.com/problems/reverse-vowels-of-a-string/) |
| **Sliding Window** | [3](https://leetcode.com/problems/longest-substring-without-repeating-characters/), [76](https://leetcode.com/problems/minimum-window-substring/), [567](https://leetcode.com/problems/permutation-in-string/), [424](https://leetcode.com/problems/longest-repeating-character-replacement/) |
| **Pattern Matching** | [28](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/), [214](https://leetcode.com/problems/shortest-palindrome/), [139](https://leetcode.com/problems/word-break/), [140](https://leetcode.com/problems/word-break-ii/) |
| **Palindromes** | [5](https://leetcode.com/problems/longest-palindromic-substring/), [9](https://leetcode.com/problems/palindrome-number/), [266](https://leetcode.com/problems/palindrome-permutation/), [647](https://leetcode.com/problems/palindromic-substrings/) |
| **Sorting & Grouping** | [49](https://leetcode.com/problems/group-anagrams/), [242](https://leetcode.com/problems/valid-anagram/), [937](https://leetcode.com/problems/reorder-data-in-log-files/), [791](https://leetcode.com/problems/custom-sort-string/) |

---

```
