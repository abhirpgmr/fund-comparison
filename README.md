# fund-comparison
A Practice Project to find the best mutual fund using correlation factor.

Mutual Funds can be a best start for those who wanted to invest in stocks but have no idea to chose between various stocks.A Mutual Fund has its money invested in proportions of different stocks depending on the category of the fund.
In this project,four funds offered by Groww (https://groww.in/) are analysed and compared based on how diversified they are.

Diversification is very important for any investment which enables us to play safe with riskier assets.It saves an individual during any crashes happening in the market and often minimises the loss when market tumbles down.

Mathematically Diversification can be measured by the value of correlation between the assets.More the correlation chances are that the assets will oscillate at same rate and hence lesser the diversification.By the same token,the converse is also true.

The top four stocks of each of the fund are taken for the analysis as they constitute for 20 percent of the entire portfolio of the fund and these 20 percent has immediate effect on the whole fund(Similar to Pareto Principle).

The funds chosen are:

1. Axis Bluechip Fund.

2. Canara Robeco Bluechip Fund.

3. ICICI Prudential Bluechip Fund.

4. Mirae Asset Emerging Bluechip Fund.

This Project consists of three parts.

a) Getting Stock data from Yahoo Finance and Calculating the Percentage Adjacent Returns on Daily Basis (%Returns = Adj.Price2 - Adj.Price1)/Adj.Price2

b) Grouping those returns as per the fund and Finding the value of 100 Rupees investment in each asset from the Percentage Adjacent Returns (Value of 100 = 100+(100*Percentage of the Adj.Return))

c) Finding the correlation matrix for the 100 Rupees Investment value for various  stocks and charting the data of stocks which have low correlation and high correlation.
