# stock-analysis
Repository for stock analysis challenge of the bootcamp course work

# All Stocks Analysis

## Overview of Project

The client Steve has asked for asssitance in analyzing the stock market for the past few years in order to better advise his parents on their financial investments. We have been given the task to create a script for the analysis and then to refactor the code to fit larger groups of data instead of the small amount we were given.  

## Results

<img width="226" alt="Stocks_Analysis_2017" src="https://user-images.githubusercontent.com/68725398/92526905-38792880-f1f4-11ea-9dc2-32d3daa287a0.png">

<img width="226" alt="Stocks_Analysis_2018" src="https://user-images.githubusercontent.com/68725398/92526938-43cc5400-f1f4-11ea-8e66-40977b2df084.png">

### Stock Performances

Stock performances has went down drastically from 2017 to 2018, as indicated in the above images. Of the original stocks, only 2 of them has shown any signs of positive returns in 2018, as opposed to 11 stocks showing positive returns in 2017. The stock "ENPH" seems to be a good investment option because it did quite well in both years' analysis.

### Execution times in Original Script vs Refactored Script

<img width="299" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/68725398/92528542-f6051b00-f1f6-11ea-9ec7-9a6dae75fad9.png">

<img width="243" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/68725398/92528599-087f5480-f1f7-11ea-8ae2-266d220c6982.png">

There does not seem to be a huge difference with the run time from the original script vs the refactored script with the differences being quite negligible (within .05 of each other). However, the original script was faster than the refactored script during each of the tested runs. This might be due to the original script not using an array to store the data and instead, opting to directly update the "All Stocks Analysis" sheet after each ticker change and immediately continuining from where it was left off on the specified year's dataset.

## Summary

- What are the advantages or disadvantages of refactoring code?

Refactoring codes are essential to a programs usage. Scripts of codes are often not perfect the first time around and needs to be refactored to make it easier to understand and/or update for a different task. This will often help with locating any bugs that might have been missed if the program is too large and cluttered.

With the above said, sometimes refactoring can causes issues if the programs are too big and is done by someone who isn't fully familiar with the code's function. Prime example being if someone who just joined a company and was asked to refactor an older program's code to solve a current issue. Refactoring a code like this might not always be the best idea, the employee may have better success to simply rewrite the code from the ground up.

- How do these pros and cons apply to refactoring the original VBA script?
The original VBA script itself is already close to being perfect, with maybe only minor differences compared to the refactored code, so refactoring the code is negligible in this instance. 
