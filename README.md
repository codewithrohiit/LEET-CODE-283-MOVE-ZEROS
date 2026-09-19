# LeetCode 283 - Move Zeroes

## Problem Statement
Given an integer array nums, move all 0's to the end
of it while maintaining the relative order of the
non-zero elements.

You must do this in-place without making a copy of
the array.

## Approach: Two Pointer

We use two pointers:
- i: Tracks the position where the next non-zero
     element should be placed.
- j: Traverses the entire array.

### Algorithm
1. Initialize i = 0.
2. Traverse the array using j.
3. If nums[j] is not zero:
   - Swap nums[i] and nums[j].
   - Increment i.
4. Continue until the array is completely traversed.

## Complexity Analysis

- Time Complexity: O(n)
- Space Complexity: O(1)

## Language
- C

## LeetCode
Problem: 283 - Move Zeroes
