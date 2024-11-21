# Iswarya-Stock-Movement-Analysis-Based-on-Social-Media-Sentiment
In this project, we analyzed the correlation between social media sentiment and stock market movements of a company by applying sentiment analysis and machine learning techniques. The project utilizes two machine learning models: Random Forest and Support Vector Regression (SVR). The analysis explores the impact of tweets, extracted from Twitter, on stock market trends using both daily and hourly sentiment aggregation. The models were evaluated using RMSE (Root Mean Squared Error) to assess their predictive accuracy.
Process Flow
Data Collection and Preprocessing
Stock Market Data: Historical stock price data was collected using the yfinance API.
Twitter Data: Tweets were retrieved using the GetOldTweets API, focusing on stock-related keywords.
Data Cleaning: Preprocessing steps included removing stop words, hyperlinks, and irrelevant text from tweets to ensure data quality.
Sentiment Analysis
Sentiment analysis was performed on the cleaned tweets using the VADER (Valence Aware Dictionary and sEntiment Reasoner) tool.
Each tweet was assigned a sentiment score, classifying it as positive, negative, or neutral. Sentiment scores were aggregated both daily and hourly to capture the sentiment's influence over time.
Data Preparation
Rows with missing values, such as incomplete price data, were handled appropriately.
Sentiment scores were merged with stock data, and the resulting dataset was divided into training and testing subsets to prepare it for model input.
Applying Machine Learning Models
Random Forest: A decision-tree-based ensemble model was used to predict stock prices due to its robustness in handling non-linear data.
Support Vector Regression (SVR): A regression model was employed to capture complex relationships between sentiment and stock movements.
Evaluation: Both models were evaluated using the RMSE metric to compare their performance. This allowed for insights into the model best suited for this dataset.

