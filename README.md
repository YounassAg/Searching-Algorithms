# Searching-Algorithms

This repository contains implementations of various searching algorithms in Python. Each algorithm is implemented in its own Python file for clarity and ease of use.

## Table of Contents

- [Linear Search](#linear-search)
- [Binary Search](#binary-search)

## Linear Search

Linear Search is a simple search algorithm that checks each element in the list sequentially until the target element is found or the list ends.

File: `Linear_Search.py`

### How It Works

The algorithm iterates through each element of the list, comparing it with the target value. If the target is found, the index of the target is returned. If the target is not found after checking all elements, the algorithm returns -1.


## Binary Search

Binary Search is an efficient search algorithm that finds the position of a target value within a sorted array. It works by repeatedly dividing in half the portion of the list that could contain the target value, until the target value is found or the search space is exhausted.

### How It Works

1. Compare the target value to the middle element of the array.
2. If the target value is equal to the middle element, return its index.
3. If the target value is less than the middle element, repeat the search on the left half of the array.
4. If the target value is greater than the middle element, repeat the search on the right half of the array.
5. If the search space is exhausted, return -1 indicating the target value is not in the array.

