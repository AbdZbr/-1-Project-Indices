# -1-Project-Indices
Two Sum Problem Solution
This repository contains a C++ solution to the classic Two Sum problem from LeetCode, implemented as part of a warm-up assignment to refresh understanding of arrays in C++.

Problem Description
Given an array of integers nums and an integer target, return the indices of the two numbers such that they add up to target. Each input has exactly one solution, and you may not use the same element twice.

Solution Approach
The solution uses an efficient hash map approach with O(n) time complexity:

Iterate through the array while storing each element and its index in an unordered map

For each element, calculate its complement (target - current element)

Check if the complement exists in the map and return the indices if found

Continue until a valid pair is found
