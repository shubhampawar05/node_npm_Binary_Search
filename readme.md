# Binary Search Algorithm

A simple npm package for performing binary search on arrays.

## Installation

You can install this package via npm:

```bash
npm install day_2_assignment_binary_search

const binarySearch = require('day_2_assignment_binary_search');

// Example 1: Searching in a sorted array
const sortedArray = [1, 3, 5, 7, 9];
const target1 = 7;
const index1 = binarySearch(sortedArray, target1);
console.log(`Target ${target1} found at index ${index1}`);

// Example 2: Searching in an unsorted array
const unsortedArray = [9, 2, 5, 1, 7];
const target2 = 5;
const index2 = binarySearch(unsortedArray, target2);
console.log(`Target ${target2} found at index ${index2}`);

// Example 3: Target not found
const target3 = 4;
const index3 = binarySearch(sortedArray, target3);
if (index3 === -1) {
  console.log(`Target ${target3} not found`);
}

