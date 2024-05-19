# Portfolio_Optimization_US
Process of selecting assets that are are optimmized fully to bear any market conditions and generate best possible returns .

This code base consists of parts
1. Importing the necessary libraries { Pandas ,Yfinance ,Numpy ,DateTime ,Scipy.optimize, amtplotlib}
2. Creating ticker symbols and gathering data of the adjusted close price for each ticker
3. Calculate Log Normal returns and make a covariance matrix of the matrix
4. Make functions for calculating : Sharpe Ratio , Expected Returns ,Standard Deviation 
5. Put up the constraints  : These can be changed for better returns /performance
6. Finally printing the optimal weights from the tickers we chose
