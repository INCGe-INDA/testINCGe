### Task Description

Exercise 1: **Weather Data Analysis Using Arrays**

**Objective:** Analyze temperature data to find the longest sequence of increasing temperatures.

**Description:**
In this exercise, students will work with arrays to analyze a dataset representing daily temperatures. The task is to develop a Haskell program that identifies the longest sequence of consecutive days with increasing temperatures. This exercise will enhance the understanding of arrays and iterative logic in Haskell.

**Requirements:**
- Read input data representing daily temperatures.
- Implement a loop to process the array.
- Determine the longest sequence of increasing temperatures.

**Hints:**

1. Begin by importing necessary modules for array handling.
   ```haskell
   import Data.Array
   ```

2. Use array indexing to iterate through temperature data.
   ```haskell
   let temperatureArray = listArray (0, n - 1) temperatures
   ```

3. Develop logic to track sequences and update the longest found.
   ```haskell
   forM_ [1 .. n-1] $ \i -> do
     -- Compare temperatureArray!i with temperatureArray!(i-1)
   ```

**Expected Skills:**
- Manipulating arrays in Haskell
- Implementing loops and conditionals
- Analyzing sequence patterns in data

By completing this exercise, students will gain practical experience in using arrays and loops for data analysis tasks, critical for developing more complex algorithms.