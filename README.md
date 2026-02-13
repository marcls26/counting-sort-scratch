# Counting Sort (Scratch Implementation)

## Overview
<In this project, I implemented an algorithm in Scratch inspired by counting sort. The algorithm uses a two-pass approach. In the first pass, it iterates through the list to determine the maximum value by conditionally comparing each element to the current largest value. This maximum value is then used to create a frequency array with enough indices to represent all possible values in the original list. In the second pass, the algorithm iterates through the original list again and increments the value at the corresponding index in the frequency array, effectively counting how many times each number appears. The sorted list can then be reconstructed by iterating through the frequency array and inserting each value according to its recorded frequency. This method is efficient when the range of values is small. However, it becomes inefficient when the maximum value is very large relative to the number of elements, as memory allocation increases based on the value range rather than the list size, creating a trade-off between time and space complexity.>

## Algorithm Steps
1. Find maximum value
2. Create frequency list
3. Count occurrences
4. Reconstruct sorted list

## Limitations
- Assumes non-negative integers
- Space complexity depends on value range
- Inefficient when range is very large

## What I Learned
- Maximum search using iteration
- Frequency arrays
- Time vs space trade-offs
