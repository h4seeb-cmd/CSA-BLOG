---
toc: false
comments: false
layout: post
author: Mirza Beg
title: FRQ Presentation Notes
description: The notes from the Cross-Review
type: tangibles
courses: { compsci: {week: 5} }
---

# Cross Review Notes

## David's 2D Arrays FRQ (2018)
- 2018
- Part A asked to find values in a certain column
- Created a variable that stored all the values, iterated through each row in order to get all of the values and print them out
- Part B asked to test whetehr or not it is allowed in sq
- ContainsDuplicates, iterated through the arrays to test whether or not the valeus are in each separate array
- Square should have all of the values in each row, but they cannot repeat in the same row or in the same column
- Checked to see whether the square contained duplicates
- Failure points, checked for errors in his code
- Error shows that there are duplicates in the same row, which is the fourth row
- Checks to see if there are duplicates in the same column
## Alex's 2D Arrays FRQ (2019)
- 2019
- Class for  a lightboard
- 2D Array with some unspecified number of rows called lights
- constructor lightboard, extantiate a new 2d array with the proper number of rows
- evaluateLight returns true or false
- Part A required use of a nested for loop and to iterate through num rows and num columns
- Generate a random number using the random integer from 1-10 to see if it is greater than or equal to 6, four values return true while 6 return false
- Testing method: created two countervariables on and off, both set to 0, used nested for loop, checked to see if each element was on or off
- Part B requires counting through every column
- Every column has the same index within a specified row
- After calculating the number of rows in each column you can see if the value would be true or false
- Tested the actual light board with true and false
## FRQ 2019, Methods and Classes
- Created a step tracker class to see if the number of steps per day would be counted
- Needed to implement three methods
- Steptracker has minimum stemps, totalsteps, activedays, and totaldays
- constructor that sets the initial values for initial methods equal to 0
- averageSteps goes on to add daily steps and divides by the total number of days
- if steps was less than 10000 a day would not be added
- if steps was greater than 10000 then a day would be added and would return a double value for the averagesteps
## Methods and Control Strucutres (2019)
- Creating functions related to a calendar
- Part A returns the number of leap years between two years, the first one being the early year and the second one being the later year
- increase number of leap years using an isLeapYear function, returns boolean value of true if it is a leap year, otherwise returns false
- Part B will return the day of the week of a given date
- a lot of fill in the blank
- day of the week of the first day of the year, subtracting 1 to account for the fact that the first day of the year starts on the first day
- represents days of the week as integer values from 0 to 6
- isLeapYear function is a boolean conditional will determine if it is a leap year, has to be divisible by 400 and not by 100 or divisible by 100 (rule for centuries)
- tests out the function with the year 2000
## 2019 FRQ for ArrayLists (FRQ 3)
- sorts out the letters of a string
- makes you iterate through a certain string using a for loop
- created a token string