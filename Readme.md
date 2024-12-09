# **Insertion Sort Algorithm**

## **Description**
This project implements the **Insertion Sort Algorithm** in JavaScript. It is a simple yet effective sorting algorithm that organizes data in ascending order by inserting elements from the unsorted part into their correct position in the sorted part.

---

## **Algorithm Explanation**

1. The algorithm starts from the second element (`arr[1]`) and considers it as the `key`.
2. Compares the `key` with all elements in the sorted part (`arr[0]` to `arr[i-1]`).
3. Moves all larger elements one position to the right to make space for the `key`.
4. Inserts the `key` into its correct position in the sorted array.
5. Repeats this process for all elements in the array.

---

## **Features**
- **Input**: An unsorted array of integers.
- **Output**: A sorted array of integers in ascending order.
- Time Complexity: **O(n²)** in the worst case, **O(n)** in the best case (when the array is nearly sorted).
- Space Complexity: **O(1)** (in-place sorting).

---
#Thanks Mattias for his help in this project.