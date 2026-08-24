 # LeetCode 1 - Two Sum

## Problem
Given an array of integers `nums` and an integer `target`, find two numbers
whose sum is equal to the target and return their indices.

## Example

### Input
nums = [2, 7, 11, 15]
target = 9

### Output
[0, 1]

## Explanation
The numbers 2 and 7 add up to the target 9.

2 + 7 = 9

Therefore, their indices are 0 and 1.

## Approach
Use a hash map to store numbers and their indices while iterating through
the array.

For each number:
1. Calculate the required number.
2. Check whether it already exists in the hash map.
3. If it exists, return the two indices.
4. Otherwise, store the current number and its index.

## Complexity
- Time Complexity: O(n)
- Space Complexity: O(n)

## Language
Python

## LeetCode
Problem #1 - Two Sum

## Difficulty
Easy

## Author
T.Nandhini
