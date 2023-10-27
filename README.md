# CPPDS_Sorting
This repository provides C++ implementations of three common sorting algorithms: Selection Sort, Insertion Sort, and Bubble Sort. Each algorithm is explained in detail, and you can find corresponding C++ code and instructions on how to use them below.

## Table of Contents
- [Selection Sort](#selection-sort)
- [Insertion Sort](#insertion-sort)
- [Bubble Sort](#bubble-sort)
- [Usage](#usage)
- [Contributions](#contributions)

## Selection Sort

Selection Sort is a straightforward comparison-based sorting algorithm. It repeatedly identifies the minimum element from the unsorted part of the array and swaps it with the first unsorted element. This process continues until the entire array is sorted.

### Algorithm

1. Find the minimum element in the unsorted part of the array.
2. Swap it with the first unsorted element.
3. Shift the boundary between the sorted and unsorted parts one position to the right.
4. Repeat steps 1-3 until the array is sorted.

### Code
You can find the Selection Sort code in the `selection sort.cpp` file.

## Insertion Sort

Insertion Sort is another straightforward sorting algorithm that constructs the final sorted array one element at a time. It selects each element from the input data and inserts it into the correct position within the sorted part of the array.

### Algorithm

1. Start with the second element (index 1) and treat it as the key.
2. Compare the key with the elements to its left and move them to the right until the correct position is found.
3. Repeat this process for each element in the array.

### Code
You can find the Insertion Sort code in the `insertion sort.cpp` file.

## Bubble Sort

Bubble Sort is a simple sorting algorithm that repeatedly moves through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process continues until no swaps are required, indicating that the list is sorted.

### Algorithm

1. Compare adjacent pairs of elements in the array.
2. If they are in the wrong order, swap them.
3. Continue this process for each element until no more swaps are needed.

### Code
You can find the Bubble Sort code in the `bubble sort.cpp` file.

## Selection Sort:
![Screenshot 2023-10-25 195208](https://github.com/Arjun378/Cpp-Sorting/assets/74441883/61beec40-a3d4-4f34-a0ae-51e090ec55fa)

## Insertion Sort:
![Screenshot 2023-10-25 195343](https://github.com/Arjun378/Cpp-Sorting/assets/74441883/966f4511-f0e9-4f0a-99d4-7b59411b994d)

## Bubble Sort:
![Screenshot 2023-10-25 195444](https://github.com/Arjun378/Cpp-Sorting/assets/74441883/f4cb1e84-53f4-4fdb-b6db-0675f42f2b3b)
