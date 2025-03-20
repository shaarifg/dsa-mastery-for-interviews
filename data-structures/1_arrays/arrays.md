Here’s your **`arrays.md`** file with **Arrays & ArrayLists combined**, structured exactly as per your **GitHub format** with **direct LeetCode links**. 🚀

---

# **📌 Arrays & ArrayList - Concepts, Patterns & LeetCode Problems**

---

## **📍 1. What are Arrays & ArrayLists?**

### **🔹 Arrays**

An **array** is a **fixed-size** contiguous memory block that stores **homogeneous** elements.

```java
int[] arr = new int[5];  // Array of size 5
int[] nums = {1, 2, 3, 4, 5};  // Pre-initialized array
```

✔ **Fast random access (`O(1)`)**  
✔ **Fixed size (Cannot be resized dynamically)**

### **🔹 ArrayList**

An **ArrayList** is a **dynamic** array implementation that can **grow or shrink** in size.

```java
List<Integer> list = new ArrayList<>();
list.add(10);  // Add element
list.remove(0);  // Remove element at index 0
```

✔ **Dynamic resizing**  
✔ **More flexible than Arrays**

---

## **📍 2. Key Operations & Methods**

| **Operation**      | **Array**                 | **ArrayList**                             |
| ------------------ | ------------------------- | ----------------------------------------- |
| **Declaration**    | `int[] arr = new int[5];` | `List<Integer> list = new ArrayList<>();` |
| **Insert Element** | `arr[i] = 10;`            | `list.add(10);`                           |
| **Access Element** | `arr[i];`                 | `list.get(0);`                            |
| **Update Element** | `arr[i] = 20;`            | `list.set(0, 20);`                        |
| **Remove Element** | `Not Possible`            | `list.remove(0);`                         |
| **Check Size**     | `arr.length;`             | `list.size();`                            |
| **Sort**           | `Arrays.sort(arr);`       | `Collections.sort(list);`                 |

---

## **📍 3. Key Techniques & Patterns**

| **Pattern**              | **When to Use?**              | **Time Complexity** |
| ------------------------ | ----------------------------- | ------------------- |
| **Two Pointers**         | Pair Sum, Remove Duplicates   | **O(n)**            |
| **Sliding Window**       | Subarrays, Longest Substring  | **O(n)**            |
| **Binary Search**        | Searching in sorted arrays    | **O(log n)**        |
| **Kadane’s Algorithm**   | Maximum Subarray Sum          | **O(n)**            |
| **Prefix Sum**           | Fast subarray sum queries     | **O(n)**            |
| **Merge Intervals**      | Overlapping interval problems | **O(n log n)**      |
| **Dutch National Flag**  | Sorting 0s, 1s, and 2s        | **O(n)**            |
| **Heap (PriorityQueue)** | Find Kth Largest Element      | **O(n log k)**      |

---

## **📍 4. LeetCode Questions for Arrays & ArrayLists**

| **Category**             | **LeetCode Problems**                                                                                                                                                                                              |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Basic Operations**     | [136](https://leetcode.com/problems/single-number/), [26](https://leetcode.com/problems/remove-duplicates-from-sorted-array/), [485](https://leetcode.com/problems/max-consecutive-ones/)                          |
| **Two Pointers**         | [167](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/), [283](https://leetcode.com/problems/move-zeroes/), [344](https://leetcode.com/problems/reverse-string/)                                    |
| **Sliding Window**       | [3](https://leetcode.com/problems/longest-substring-without-repeating-characters/), [76](https://leetcode.com/problems/minimum-window-substring/), [209](https://leetcode.com/problems/minimum-size-subarray-sum/) |
| **Binary Search**        | [33](https://leetcode.com/problems/search-in-rotated-sorted-array/), [74](https://leetcode.com/problems/search-a-2d-matrix/), [153](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)           |
| **Kadane’s Algorithm**   | [53](https://leetcode.com/problems/maximum-subarray/), [152](https://leetcode.com/problems/maximum-product-subarray/)                                                                                              |
| **Prefix Sum**           | [560](https://leetcode.com/problems/subarray-sum-equals-k/), [238](https://leetcode.com/problems/product-of-array-except-self/)                                                                                    |
| **Merge Intervals**      | [56](https://leetcode.com/problems/merge-intervals/), [57](https://leetcode.com/problems/insert-interval/)                                                                                                         |
| **Dutch National Flag**  | [75](https://leetcode.com/problems/sort-colors/)                                                                                                                                                                   |
| **Heap (PriorityQueue)** | [215](https://leetcode.com/problems/kth-largest-element-in-an-array/)                                                                                                                                              |

---

## **📍 5. Best Practices**

✔ **Use `ArrayList` instead of Arrays if resizing is needed**.  
✔ **For frequent modifications, `LinkedList` is better than `ArrayList`**.  
✔ **Use `Arrays.sort()` for sorting small arrays; for large, use `PriorityQueue` or QuickSort**.  
✔ **Use `binary search` for faster searching in sorted arrays**.  
✔ **For interval merging problems, always `sort` the array first**.

---
