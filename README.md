# DJIA-30-Stock-Time-Series-2006-2018


Date: 27th August 2025

# **1. Summary**
The Dow Jones Industrial Average (DJIA) is one of the most widely recognized stock market indices, comprising 31 prominent U.S. companies. This project analyzes historical stock price data of these companies from 2006 to 2018. The objective of the analysis is to evaluate the performance of individual stocks, identify yearly trends, and assess correlations among stocks to provide insights into overall market behavior.

# **2. Objective of the Analysis**
1.	To analyze yearly and overall performance of individual DJIA stocks.
2.	To identify long-term trends and patterns in stock prices.
3.	To create a comprehensive dashboard for interactive exploration of stock data.

# **3. Data Description**
The dataset comprises historical price data for each of the 31 DJIA companies between 2006 and 2018. Key columns include:
1.	**Date:** Trading day.
2.	**Open, High, Low, Close:** Stock prices for each day.
3.	**Volume:** Number of shares traded.
4. **Stock Name:** Company identifier (added during data transformation).

# **4. Data Source**
The dataset used for this analysis was obtained from Kaggle, which provides historical stock market data, including daily open, high, low, close, and volume prices for publicly traded companies.

# **5. Methodology**
## 5.1 Data Loading
    1.	All 33 CSV files containing daily stock prices were directly imported into Power BI.
    2.	Each file represented one company’s historical stock data.
## 5.2 Data Transformation in Power Query
    1.	The 33 individual files were combined into a single table to simplify analysis.
    2.	Null columns and null values were removed to ensure data accuracy.
    3. 	A Date Calendar was created to facilitate time-based analysis.
## 5.3 Data Modeling & Measures (DAX)
    1.	Yearly Return: Calculated as the percentage change between the first and last closing price of each year.
    2. 	Average Closing Price: Used to analyze overall stock performance over time.
    3.	Daily Change: Calculated as the difference berween the opening stock price and closing stock price
    4.  Total Volume: Used to analzye the total volume of per stock
## 5.4 Visualization: An interactive Power BI dashboard was developed with:
    1.	Slicers for Stock Name and Year for dynamic filtering.
    2.	Line charts showing stock price trends over time.
    3.	Bar charts ranking stocks by yearly returns.

# **6. Key Findings**
1.	Several stocks demonstrated consistent upward trends, particularly in the technology and healthcare sectors.
2.	2008–2009 showed significant volatility due to the global financial crisis, with most stocks experiencing sharp declines.
3.	Positive recovery trends were observed post-2010, with certain companies outperforming the index average.

# **7. Recommendations**
1.	Diversify portfolios across sectors to mitigate risk, as high correlations indicate that sector downturns can impact multiple stocks.
2.	Monitor technology and healthcare stocks closely, as these showed strong, consistent growth.
3.	Use the interactive dashboard for ongoing trend monitoring and investment decision-making.

# **8. Conclusion**
This analysis of the DJIA 31 Stock Time Series (2006–2018) provided valuable insights into stock performance trends, and market dynamics over a decade. By consolidating multiple files into a single dataset, leveraging Power BI’s data modeling capabilities, and creating dynamic visualizations with slicers, the project successfully enables in-depth, interactive market analysis.




