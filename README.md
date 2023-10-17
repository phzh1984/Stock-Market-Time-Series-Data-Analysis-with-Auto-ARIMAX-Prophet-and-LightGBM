# Stock-Market-Time-Series-Data-Analysis-with-Auto-ARIMAX-Prophet-and-LightGBM

This repository hosts an in-depth analysis of time series data related to the stock market. The dataset used in this project comprises the price history and trading volumes of the fifty stocks in the NIFTY 50 index from the National Stock Exchange (NSE) of India. The data is provided at a daily granularity, with pricing and trading values distributed across CSV files for each stock. Additionally, a metadata file contains macro-level information about the individual stocks. The dataset covers a substantial time frame, from January 1, 2000, to April 30, 2021.

About Time Series Data:

Time series data inherently consists of four key components, which play a crucial role in understanding and modeling stock market behavior:

Trend Component: This component represents variations that exhibit reasonably predictable patterns over an extended period. It encompasses long-term movements in stock prices, reflecting overall market trends.

Seasonality Component: Seasonality refers to regular and periodic variations that repeat themselves over specific time intervals. In the context of the stock market, seasonality might manifest on daily, weekly, monthly, or seasonal time scales.

Cyclical Component: The cyclical component corresponds to variations that align with broader business or economic cycles. It captures the 'boom-bust' patterns or unique cycles associated with specific industries or sectors.

Random Component: The random component, often referred to as noise or residual, represents erratic fluctuations that cannot be classified under the three components mentioned above. These unpredictable variations are crucial to modeling market volatility.

Analysis Tools:

This repository explores various time series analysis techniques and forecasting models, including:

Auto ARIMAX: Auto ARIMAX is employed as a baseline model for time series forecasting. It offers the advantage of automated parameter selection and has been a popular choice for modeling time series data.

Prophet: Prophet, developed by Facebook, is a robust tool for forecasting time series data. It excels in capturing non-linear trends, seasonal patterns, and holiday effects. Its versatility makes it a valuable asset in this analysis.

LightGBM: LightGBM, a gradient boosting framework, is utilized for time series prediction. It brings powerful machine learning capabilities to the task and is known for its efficiency, particularly when dealing with structured data like stock market information.
