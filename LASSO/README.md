### LASSO and Ridge Regression in Python.

- Initially wanted to have a LASSO Regression model following a tutorial by Datacamp:(here)[https://www.datacamp.com/tutorial/tutorial-lasso-ridge-regression].
- A couple of problems were encountered:
* Sklearn stopped shipping bostonhousing dataset.
* Had to look for it from another source which had inconsistencies relative to what the tutorial had used.
* Their correlation heatmap was rather phased out(some indexes didn't exist).

- Opted for california housing dataset which didn't have as much collinearity as i needed for play.
- Encountered a "engine" use while reading a .xls dataset( the required engine is xlrd)
- TODO!
1. Create a utils library for functions for reading data and other repetitive tasks while working with data.
2. Write a tutorial for my workflow, for myself as i learn.
3. Will work through the boston dataset regardless, 
4. Learn how to interpret box plots and heatmaps better and efficiently.
