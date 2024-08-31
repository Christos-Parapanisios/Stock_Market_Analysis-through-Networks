## Stock_Market_Analysis-through-Networks
In the folowing I tried to identify and analyze the relationships between different stocks in the S&P 500 index using network theory and statistical methods.

##### Approach
- Collect the stock data for all S&P 500 components from 04/January/2010 till 29/December/2023 from yahoo finance.
- Compute log returns for the S&P 500 components for same time period
- Compute the correlation matrix for the above log returns
- Find out the Top n central and peripheral stocks based on the following network topological parameters:
  - Degree centrality
  - Closeness centrality
  - Betweenness centrality
  - Eigenvector centrality
  - Distance on Degree Criterion
  - Distance on Correlation Criterion
  - Distance on Distance Criterion
  - Closeness and Eigenvector Centrality
  - Normalize and combine centrality scores
  - Ranking of Stocks using Centrality and Distance-Based Metrics
- Simulate the performance of Central and Peripheral portfolios against new historical data of the year 2024 for the S&P 500.

**Note:** This is an open-source notebook that I developed for my personal research as a Data Scientist, it's purpose is not intended for investment recommendations or propositions.
