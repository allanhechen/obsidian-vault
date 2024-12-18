## 1. Identify the best theoretical time complexity of the solution

There is no point trying to find a better solution that doesn't exist (ex. finding min of unsorted array must mean that we look at each element at least once).

## 2. Identify overlapping and repeated computation

Brute force solutions often execute the same operations over and over again. Think about the operations being done and how one might reuse results from before.

## 3. Try different data structures

Different data structures serve different purposes (ex. lookup is the slowest -> use a hashmap).

___
## 4. Change data in-place

Usually not good idea to do in practice, but in Leetcode questions it might be a good idea to reduce new space assigned.

___
Retrieved from [Tech Interview handbook](https://www.techinterviewhandbook.org/coding-interview-techniques/)