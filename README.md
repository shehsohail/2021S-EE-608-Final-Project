# 2021S-EE-608-Final-Project: Stock Portfolio Optimization
This repositiory is for EE608 Spring 2021 Final Project: Stock Portfolio Optimization.

### Team Members:
SHEHPAR SOHAIL and MICHAEL HODGETTS

### Data Set:
The data for stocks used is located in the file "Stocks.csv". The file is provided in this repository.
The file contains a list of stocks that have performed in the last 50 days.

For each stock, the following information is provided:
1. Symbol
2. Symbol link
3. Company Name
4. Last Price
5. Dividend
6. 50-DMA
7. 50-DMA Chg
8. 50-DMA Chg %
9. Rate of Return
10. 1yr Target Est
11. Beta
12. Sector (Metal/Bond, Health/Pharm, Tech, Bank, Retail)

### Running of the Code:
Before running the code, the file with the data for stocks ("Stocks.csv") needs to be downloaded and put in the same folder as the code.
Step through the code by pressing Shift + Enter.

### Final Results:
After running the code to the final steps, maximum rate of return is provided followed by two tables.
Table 1 lists out the stock symbol, stock name, number and value of stocks to achieve maximum rate of return, and sector.
Table 2 lists out the constraints results. It compares the goal value vs. actual value.

### Conclusions:
This project was a good example of maximizing a solution with many constraints. Performing this task without an optimization framework would have been challenging to solve.

Optimization problems based on mathematical operations allow the user to expand the complexity of a problem (constraints, volume, etc.) or accuracy without too much effort.  

For our solution, the choices it made for the decision variables seemed logical and fit almost all the constraints.

Using python is a better approach than Excel based solver solutions. We can input large datasets automatically or on a regular basis and use various methods in the python library to solve various optimization problems.

Our model’s rate of return is very sensitive to the constraints we imposed.  In the future, we can try to reduce sensitivity so we can reduce large swings in rate of return if one stock or another is chosen.

Finally, optimization methods help users solve complex problems and allow us to scale the scope and dataset volume without too much lift. 
