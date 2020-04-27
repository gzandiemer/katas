# JS Kata 2

- Date: 13/04/2020
- Tags: fundamental JS
- Source: codewars.com: 

## Description 

### Delete Redundant Occurrences of an Element
Given an array arr and a number N, create a new array that contains each number of the array at most N times without reordering.

For example if N = 2, and the input is [1,2,3,1,2,1,2,3], you take [1,2,3,1,2], drop the next [1,2] since this would lead to 1 and 2 being in the result 3 times, and then take 3, which leads to [1,2,3,1,2,3].

Example:
- deleteNth ([1,1,1,1],2) // return [1,1]
- deleteNth ([20,37,20,21],1) // return [20,37,21]