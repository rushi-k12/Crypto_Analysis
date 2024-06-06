### Crypto Analysis Project
## Overview
This project involves web scraping data from crypto.com, performing data cleaning and preprocessing, building a predictive model using neural networks, and creating a Power BI report for visualization. The goal is to predict cryptocurrency prices based on various features and provide insightful visualizations.

##Tasks Performed
## 1. Web Scraping
Scraped data for around 21,000 cryptocurrencies from crypto.com using Scrapy.
Extracted key features including:
Name
Price
24-hour Change
24-hour Volume
Market Cap
## 2. Data Cleaning and Preprocessing
Handled missing values by filling them with the mean values of their respective columns.
Converted data types of relevant columns for consistency:
'price' to float
'change_24h' to float
'volume_24h' to float
'market_cap' to float
Ensured data quality by verifying and correcting inconsistencies.
## 3. Model Building
Split the dataset into training and testing sets.
Standardized the features using StandardScaler to ensure uniformity.
Built a neural network model using TensorFlow and Keras:
The model architecture includes multiple Dense layers with ReLU activation and Dropout layers for regularization.
Compiled the model using the Adam optimizer and mean squared error loss function.
Trained the model on the training data and evaluated it on the test data.
## 4. Power BI Report
Created a Power BI report to visualize the scraped and processed data.
Included various visualizations to provide insights into the cryptocurrency market, such as:
Price trends
Market cap distribution
24-hour volume and change analysis
Integrated interactive elements to allow users to explore the data dynamically.
