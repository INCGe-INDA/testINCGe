### Task Description

Exercise 1: Temperature Data Analysis

**Description:**
In this exercise, students will work with arrays to analyze temperature data collected over a month. This task simulates real-world data handling, focusing on implementing loops to process and extract meaningful information from the data set.

**Objective:**
Develop proficiency in using arrays and loops to analyze and manipulate data.

**Requirements:**
- Read and store daily temperature data for a month.
- Calculate the average monthly temperature.
- Identify the highest and lowest temperatures and their respective days.

**Hints:**
1. Initializing an array and storing sample temperature data.
   ```cpp
   const int DAYS_IN_MONTH = 30;
   double temperatures[DAYS_IN_MONTH] = { /* sample temperatures */ };
   ```

2. Loop structure to iterate over the array for calculating averages.
   ```cpp
   double total = 0;
   for (int i = 0; i < DAYS_IN_MONTH; i++) {
       total += temperatures[i];
   }
   ```

3. Finding maximum and minimum values in the array.
   ```cpp
   double maxTemp = temperatures[0];
   double minTemp = temperatures[0];
   int maxDay = 0, minDay = 0;
   for (int i = 1; i < DAYS_IN_MONTH; i++) {
       if (temperatures[i] > maxTemp) {
           maxTemp = temperatures[i];
           maxDay = i;
       }
       if (temperatures[i] < minTemp) {
           minTemp = temperatures[i];
           minDay = i;
       }
   }
   ```

**Expected Outcome:**
An application that efficiently performs temperature data analysis using arrays and loops, with correct identification of average, maximum, and minimum temperatures and their respective days.