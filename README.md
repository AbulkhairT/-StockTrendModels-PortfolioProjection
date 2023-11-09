# -StockTrendModels-PortfolioProjection

Comprehensive Stock Market Analysis and Portfolio Value Projection using Polynomial Regression, Linear Regression, and Trend Change Detection

T-Mobile and S&P500 stocks were analyzed and compared based on different analytical models such as: 

Polynomial Trend Analysis for Trading Signals: Implementation and comparison of linear, quadratic, and cubic polynomial models to predict future weekly stock price trends. The models assign "green" or "red" labels for the upcoming week based on the closing prices of the previous \( W \) weeks, indicating potential investment actions.

Model Accuracy Assessment: Evaluation of the predictive accuracy of each polynomial model over a range of window sizes \( W \) for the first year's data. The optimal window size is determined based on the highest accuracy.

Yearly Strategy Implementation and Comparison: Application of the best-performing window sizes and polynomial degrees to the second year's data to predict weekly labels and implement trading strategies.

Trend Change Detection Using F-tests: Application of F-tests to monthly stock data to detect statistically significant changes in pricing behavior. This method identifies potential shifts in market trends, informing investment decisions.

Linear Regression for Day Trading: Construction of a linear regression model based on a selected window of daily closing prices to inform day trading strategies. The strategy involves taking long or short positions to capitalize on predicted price movements.

Performance Evaluation: Calculation of the average profit/loss per trade for long and short positions, the average duration of these positions, and a comparison of the trading outcomes between the two years.


Years 2017 and 2018 were analyzed, the first year was traning data, and year 2018, which is second year was the testing data. 
Results: 
   For S&P500: the optimal profits and loss window for year 2017:
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/ba52303f-a9fa-456f-9cc2-d0003eec4559">
   Optimal W and average profits/losses: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/8448c0c5-4e46-47bb-b3b1-139e1683185f">
   Visualization: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/4afb45ff-b22a-44d0-8d2a-dd8de3cfd56a">
R^2
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/03c59b34-13fa-4a72-b7ba-d502b65cee30">
   Number of Long, Short positions for year 2 and average profits/losses per year 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/f7f21697-837d-41c5-9830-85bf72bab22b">
   Accuracy for different polynomials and visualization vs window sizes: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/1938f0e8-6af1-40e1-939b-cfb5ad9af1e1">
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/c3c1ed6c-afaa-46a1-968c-cf10b735cfe4">
   Best window sizes:
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/ecc5d54f-89d8-45f2-87fd-6649c1c8fc70">
Value of portfolio based on trading strategies for year 2 (for each d using the ”best” values for W from year 1 that were found):
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/0fc881a0-a514-4878-b08e-6cb1b5f89398">
   Significant chages for the stock for both years: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/e44436ae-90af-43b3-9ceb-2acc047457f2">


Optimal value of W: 
   - For year 1, we computed the average P/L per trade for window sizes  W = 5,6,...,30 .
   - We plotted these values and found the optimal window size to be 15.

  R^2 values for year 2:
   - Using W = 15 from year 1, we computed the R^2  for each day in year 2.

  Trading transactions for year 2:
   - With  W = 15, I found there were 16 long positions and 16 short position transactions in year 2.

  Average P/L for trades in year 2:
   - I calculated the average profit/loss per long position and short position trade in year 2, which were approximately $-2.9 and -$1.006, respectively.

  Average number of days for transactions in year 2:
   - I determined the average number of days for long positions was about 4.04 days and for short positions was about 4.47 days.
     
  Second W was the best for the trading strategy, bringing the least losses 






For T-Mobile: 
   The optimal profits and loss window for year 2017: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/7d774421-5fe2-4607-954c-f9808c90f852">
   Optimal W and average profits/losses: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/1dba7cfc-72c3-430c-9e04-273320b577e0">
   Visualizaiton:
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/480ca0ed-1a15-4bc0-a5a8-584fc2cf20ab">
R^2 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/c76e3934-7d3e-4ea7-a7a4-000cd5a7a2af">
   Number of Long, Short positions for year 2 and average profits/losses per year 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/c30f8a91-d698-4db4-afcf-f37f02884791">
   Accuracy for different polynomials and visualization vs window sizes: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/9e2879ba-6e34-407f-ac3e-d44228067525">
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/eade3fed-ef9b-4baf-bd4e-f40b1ddd27de">
   Best window sizes: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/6f707b79-7f91-47d1-862c-5a9ef9ae45a2">
   Value of portfolio based on trading strategies for year 2 (for each d using the ”best” values for W from year 1 that were found):
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/92bbeae1-4857-493e-9a61-8dc7f53d9fb6">
   Significant chages for the stock for both years: 
<img width="399" alt="image" src="https://github.com/AbulkhairT/-StockTrendModels-PortfolioProjection/assets/125773898/625f0a56-95f4-46fe-a7b1-ba3d0db4b9a9">

OOptimal value of W: 
   - For year 1, we computed the average P/L per trade for window sizes  W = 5,6,...,30 .
   - We plotted these values and found the optimal window size to be 28.

  R^2 values for year 2:
   - Using W = 28  from year 1, we computed the R^2  for each day in year 2.

  Trading transactions for year 2:
   - With  W = 28, I found there were 13 long position and 15 short position transactions in year 2.

  Average P/L for trades in year 2:
   - I calculated the average profit/loss per long position and short position trade in year 2, which were approximately $0.50 and -$0.07, respectively.

  Average number of days for transactions in year 2:
   - I determined the average number of days for long positions was about 6.7 days and for short positions was about 6.5 days.

  Second W was the best for the trading strategy, bringing the least losses

Summary
For year 1, For SPY the number of long positions is 26- duration is 4 days and short positions is 19 – duration is 4.5 days, average profit per trade is 1.08. For TMUS it is long 18- average days 6.7, 12 
short positions – 6.5 days, average profit per trade is 1.1. For year 2, for SPY there are 16 long and 16 short positions, both are giving losses -2.9 and -1.06, while for TMUS it is 13 long and 15 short, 
for long there is average profit per trade of 0.5 while for short there is loss of -0.06 on average. Results are very different, especially average profit and loss. W’s are also different, for TMUS it is 28, 
and for SPY it is 15. 








