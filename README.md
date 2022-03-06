# stock-analysis

#  VBA Challenge

## Overview of Project: Explain the purpose of this analysis.
The purpose of this code is to create a dataset for Steve to do research for his parents and to expand the data set that we initially had for Green stock to include the entire stock market over the last few years, but for thousands of stocks. 

In Challenge 2 I refactored Module 2 solution code in order to determine if the refactoring code made the VBA script run faster for such a huge set of thousands of stocks in order to make the analysis easier and more efficient. This helped myself and our character Steve make the data easier to read. 

## Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

(Having issues attaching images to Read Me documents - professor Cenan is aware of this issue).

I ran the subrounting through the list of ticker symbols, stock activity and checking for the volume data and price for each ticker in the listed array in order to output these findings.

2017 results:
 - The ticker with the highest trading volume was FSLR.
 - The ticker with the best rate of return was (DQ)


2018 results:
- The ticker with the highest trading volume was ENPH
- The ticker that had the best return was DQ

I was able to reduce processing time by about half a second for both 2017 to 2018 data by changing variables into arrays which helped memory/ram.

## Sumary: In a summary statement, address the following questions:

* 1. What are the advantages or disadvantages of refactoring code?
The advances of refactoring code is that it is easier to clean-up larger data sets and use less memory. The disadvantages is that is a difficult process (at least fo me) and requires quite a bit of time due to the the complexity. It is extremely time consuming. 

* 2. How do these pros and cons apply to refactoring the original VBA script?
The pros and cons need to be taken into consideration for the programmer and whether or not the time investment is worth the output for a data set. The end resuls is that it is easier to understand the data and have accurate information from dense data.
