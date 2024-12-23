# Unsupervised-Learning-Project-7-Trade-and-Ahead
Unsupervised Learning: Trade & Ahead
Problem Statement
Context
The stock market has consistently proven to be a good place to invest in and save for the future. There are a lot of compelling reasons to invest in stocks. It can help in fighting inflation, create wealth, and also provides some tax benefits. Good steady returns on investments over a long period of time can also grow a lot more than seems possible. Also, thanks to the power of compound interest, the earlier one starts investing, the larger the corpus one can have for retirement. Overall, investing in stocks can help meet life's financial aspirations.

It is important to maintain a diversified portfolio when investing in stocks in order to maximise earnings under any market condition. Having a diversified portfolio tends to yield higher returns and face lower risk by tempering potential losses when the market is down. It is often easy to get lost in a sea of financial metrics to analyze while determining the worth of a stock, and doing the same for a multitude of stocks to identify the right picks for an individual can be a tedious task. By doing a cluster analysis, one can identify stocks that exhibit similar characteristics and ones which exhibit minimum correlation. This will help investors better analyze stocks across different market segments and help protect against risks that could make the portfolio vulnerable to losses.

Objective
Trade&Ahead is a financial consultancy firm who provide their customers with personalized investment strategies. They have hired you as a Data Scientist and provided you with data comprising stock price and some financial indicators for a few companies listed under the New York Stock Exchange. They have assigned you the tasks of analyzing the data, grouping the stocks based on the attributes provided, and sharing insights about the characteristics of each group.

Data Dictionary
Ticker Symbol: An abbreviation used to uniquely identify publicly traded shares of a particular stock on a particular stock market
Company: Name of the company
GICS Sector: The specific economic sector assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
GICS Sub Industry: The specific sub-industry group assigned to a company by the Global Industry Classification Standard (GICS) that best defines its business operations
Current Price: Current stock price in dollars
Price Change: Percentage change in the stock price in 13 weeks
Volatility: Standard deviation of the stock price over the past 13 weeks
ROE: A measure of financial performance calculated by dividing net income by shareholders' equity (shareholders' equity is equal to a company's assets minus its debt)
Cash Ratio: The ratio of a company's total reserves of cash and cash equivalents to its total current liabilities
Net Cash Flow: The difference between a company's cash inflows and outflows (in dollars)
Net Income: Revenues minus expenses, interest, and taxes (in dollars)
Earnings Per Share: Company's net profit divided by the number of common shares it has outstanding (in dollars)
Estimated Shares Outstanding: Company's stock currently held by all its shareholders
P/E Ratio: Ratio of the company's current stock price to the earnings per share
P/B Ratio: Ratio of the company's stock price per share by its book value per share (book value of a company is the net difference between that company's total assets and total liabilities)
Importing necessary libraries and data
# Installing the libraries with the specified version.
# uncomment and run the following line if Google Colab is being used
# !pip install scikit-learn==1.2.2 seaborn==0.13.1 matplotlib==3.7.1 numpy==1.25.2 pandas==1.5.3 yellowbrick==1.5 -q --user
# Installing the libraries with the specified version.
# uncomment and run the following lines if Jupyter Notebook is being used
# !pip install scikit-learn==1.2.2 seaborn==0.13.1 matplotlib==3.7.1 numpy==1.25.2 pandas==1.5.2 yellowbrick==1.5 -q --user
# !pip install --upgrade -q jinja2
Note: After running the above cell, kindly restart the notebook kernel and run all cells sequentially from the start again.

 
Data Overview
Observations
Sanity checks
 
Exploratory Data Analysis (EDA)
EDA is an important part of any project involving data.
It is important to investigate and understand the data better before building a model with it.
A few questions have been mentioned below which will help you approach the analysis in the right manner and generate insights from the data.
A thorough analysis of the data, in addition to the questions mentioned below, should be done.
Questions:

What does the distribution of stock prices look like?
The stocks of which economic sector have seen the maximum price increase on average?
How are the different variables correlated with each other?
Cash ratio provides a measure of a company's ability to cover its short-term obligations using only cash and cash equivalents. How does the average cash ratio vary across economic sectors?
P/E ratios can help determine the relative value of a company's shares as they signify the amount of money an investor is willing to invest in a single share of a company per dollar of its earnings. How does the P/E ratio vary, on average, across economic sectors?
 
Data Preprocessing
Duplicate value check
Missing value treatment
Outlier check
Feature engineering (if needed)
Any other preprocessing steps (if needed)
 
EDA
It is a good idea to explore the data once again after manipulating it.
 
K-means Clustering
 
Hierarchical Clustering
 
K-means vs Hierarchical Clustering
You compare several things, like:

Which clustering technique took less time for execution?
Which clustering technique gave you more distinct clusters, or are they the same?
How many observations are there in the similar clusters of both algorithms?
How many clusters are obtained as the appropriate number of clusters from both algorithms?
You can also mention any differences or similarities you obtained in the cluster profiles from both the clustering techniques.

Actionable Insights and Recommendations
