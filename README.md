# Assignment2
Assignment2 of Algorithm Trading

This assignment is based on the blog 'Portfolio Optimization with Python'.
According to this blog, I walk through using convex optimization to allocate a stock portfolio so that it maximizes return for a given risk level. We’ll use real data for a mock portfolio, and solve the problemusing Python. 

Considering the situation where we solve an optimization problem to find the combination of stocks that maximizes expected return for agiven risk level.
We can use the quantity  as a measure of risk for a given portfolio allocation with covariance. Our objective is to minimize it. This objective function is a convex function, meaning that we’re able to formulate a convex optimization problem, specifically a quadratic program (QP), to find its minimum.

I adjust the code shown here is from portfolio.py and uses code in stocks.py, which pulls stock data from Yahoo Finance.
I use the Python3.9 as the environmnet. Choose the the portflio of 9 stocks, from the start time 2005/01/01 to the end time 2010/01/01, with a quote price as a result.
