# Module 4 Challenge

NAV data from four portfolio funds was analyzed to evaluate investment potential based on several key metrics including daily returns, standard devations, Sharpe Ratios and betas.

## Results

After analyzing performace, volatility, risk and risk-return profiles of each of the four portfolios and the S&P 500, Berkshire Hathaway and Tiger Global were selected for further evaluation to diversify our portfolio. Both of these funds had significantly higher Sharpe Ratios than the other two funds as shown below:
![SharpeRatios](/Images/Sharpe_Ratios.png)
The 60-day rolling covariance of each of these two funds was calculated which allowed us to calculate the beta for each fund by comparing the covariance to the S&P 500 rolling variance. BH had an average beta of 0.22 compared to TG's average beta of 0.03. This shows that BH is more sensitive to the market, however after considering the historical returns of the two funds, we have decided to add the Berkshire Hathaway fund to diversify our portfolio since, although it is a riskier fund, it has generated significantly higher returns.
![CummulativeReturns](/Images/Cumulative_Returns.png)

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For financial data analysis tools
* [numpy](https://numpy.org/) - For numerical functions to aid in financial calculations
* [matplotlib](https://matplotlib.org/) - For data visualizations

## Contributors

Starter code for this app was provided by the GWU Fintech Bootcamp program. Updates to that code to fulfill the analysis were done by Peter Lefebvre (peter.c.lefebvre@gmail.com)

## License

MIT License
