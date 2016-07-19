# Modeling-Time-Series-Data
 Live Session 9 Assignment

The live session assignment is due on Wednesday, July 20. 
Here is the assignment:

1)	Go through the electric equipment example. 

Code to load data:
library(fpp) #fpp package must be installed first
data(hsales)

-	Plot the time series. Can you identify seasonal fluctuations and/or a trend? 
-	Use a classical decomposition to calculate the trend-cycle and seasonal indices. 
-	Do the results support the graphical interpretation from part (a)? 
-	Compute and plot the seasonally adjusted data. 
-	Change one observation to be an outlier (e.g., add 500 to one observation), and recompute the seasonally adjusted data. What is the effect of the outlier? 
-	Does it make any difference if the outlier is near the end rather than in the middle of the time series? 
-	Use STL to decompose the series. 

2)	I’ll assign a stock for each student.

•	First go through the r code which used for S&P500.

Then do the following for the assigned stock.
•	Download the data.
•	Calculate log returns.
•	Calculate volatility measure.
•	Calculate volatility measure with a continuous lookback window.
•	Plot the results with a volatility curve overlay.

Deliverable is a link to R Markdown file on GitHub.
