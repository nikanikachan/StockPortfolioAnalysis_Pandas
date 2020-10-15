# A Whale Off the Port(folio)
### Unit 4 pandas homework

## Performance Analysis

Looking at the plot of each portfolio's daily returns, it is not immediately obvious if any of them outperformed the S&P 500. However, looking at a plot of cumulative returns shows that all portfolios outperformed the S&P 500.

![Returns](https://i.ibb.co/XkGZHzB/Returns.png)


![Cumulative Returns](https://i.ibb.co/72GXKf7/Cumulative-returns.png)



## Risk Analysis

The Box plot shows that Tiger Global Management has the largest spread and the S&P 500 has the smallest spread. 

![Box plot](https://i.ibb.co/Wcrxb1v/Boxplot.png)

Berkshire Hathaway, Tiger Global Mgt and Algo 2 portfolios have higher standard deviation than the S&P500.These portfolios are riskier than the benchmark. 

| Portfolio | Standard Deviation |
| ------ | ----------- |
| BERKSHIRE HATHAWAY INC   | 0.012831 |
| TIGER GLOBAL MANAGEMENT LLC   |  0.010824 |
| Algo 2   |  0.008466 |
| S&P 500   |  0.008135 |
| Algo 1   |  0.007988 |
| SOROS FUND MANAGEMENT LLC   |  0.007842 |
| PAULSON & CO.INC   |  0.006977 |



## Rolling Statistics

#### Rolling standard deviation

![rolling SD](https://i.ibb.co/8gqbYT7/rolling-SD.png)

#### Correlation

The returns of Paulson & Co. Inc most closely mimics the S&P 500. This portfolio has the highest positive correlation with the S&P 500. The only other portfolio with a positive correlation is Soros Fund Mgt. The rest of the portfolios show a negative correlation with the benchmark.

![heatmap](https://i.ibb.co/bvNs728/heatmap.png)

#### Beta

I looked at the beta of Soros Fund Mgt and it shows a low positive beta coefficient of 0.0005. The 60 day rolling Beta shows varying sensitivity to the S&P 500. 

![sorosbeta](https://i.ibb.co/HgmCRJT/rollingbetasoros.png)




## Sharpe Ratios

Per unit of risk, the data shows that the algo strategies outperform the benchmark. The Algo 1 portfolio has the highest Sharpe Ratio of 1.36, this algo portfolio outperformed both the whale portfolios and the S&P 500. The Algo 2 portfolio outperformed the S&P 500 and all the whale portfolios except for Berkshire Hathaway.

| Portfolio | Sharpe Ratio |
| ------ | ----------- |
| Algo 1   | 1.369589 |
| BERKSHIRE HATHAWAY INC   |  0.606743 |
| Algo 2   |   0.484334 |
| SOROS FUND MANAGEMENT LLC   |  0.342894 |
| TIGER GLOBAL MANAGEMENT LLC   |  -0.130186 |
| PAULSON & CO.INC.   |  -0.491422 |
| S&P 500   |  -0.518582 |



## Custom Portfolio

For the custom portfolio, I chose 3 tech stocks: Amazon, Facebook and Google. I compared a portfolio with each of these stocks equally weighted to the S&P 500, whale portfolios, and algo portfolio returns. Below is a summary of the results:

- My custom portfolio is riskier compared to all other portfolios, it has higher standard deviation than the rest of the portfolios.

- My custom portfolio has the second highest sharpe ratio. The Algo 1 strategy has more return per unit of risk compared to my portfolio.

- My custom portfolio is negatively correlated with the S&P 500 but positively correlated with the whale and algo portfolios.

- For Beta, I used the TX 60 index as benchmark. My custom portfolio has a positive Beta which indicates that it generally moved in the same direction as the benchmark.

![custombeta](https://i.ibb.co/88k0h9D/rollingbetacustom.png)