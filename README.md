COUNT SORT IN C (MAX VALUE NOT GIVEN)

This repository contains a C program that implements the Count Sort algorithm.
In this special case, the maximum element is NOT given beforehand. The program first finds the maximum value from the input array and then performs Count Sort.

---

AIM

To write a program in C to implement the Count Sort algorithm where the maximum element is dynamically found from the given data.

---

ALGORITHM

1. Read the number of elements (n).
2. Input n elements into an array.
3. Find the maximum value in the array.
4. Create a count array of size (max + 1) and initialize all elements to 0.
5. Store the frequency of each element in the count array.
6. Reconstruct the sorted array by checking the count array.
7. Print the sorted array.

---

FEATURES

- Maximum element is NOT given manually.
- Maximum value is found from the input data.
- Efficient for sorting non-negative integers.
- Time complexity: O(n + k), where k is the maximum value.

---

SAMPLE INPUT

Enter number of elements: 6
Enter elements: 4 2 2 8 3 3

SAMPLE OUTPUT

Sorted array: 2 2 3 3 4 8

---

AUTHOR

Shivam Kumar Rao

---

SUBJECT

Data Structures and Algorithms
Count Sort Implementation in C