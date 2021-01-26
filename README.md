# Price Prediction for RAMs
Machine Learning about Price Prediction for RAMs(with several important regression models)(WebScraping with BeautifulSoup)

To predict the sale prices I am using the following regression algorithms: Linear Regression, Ridge regression, Lasso regression , Polinomial Regression, PLS Regression, PCR Regression and lastly Elastic Net regression algorithm. These algorithms can be feasibly implemented in python with the use of the scikit-learn package. Finally, I will conclude which model is best suitable for the given case by evaluating each of them using the evaluation metrics provided by the scikit-learn package.

## The Scenario of Project
Let’s say I’m working for a company that produces ram, and my boss asked me for help about pricing for a new model that we will produce soon. He wants me to create a model using the price data of RAMs with similar features in our competitors. He expects this model algorithm to give correct prices.

Or I want to use a nice computer that I will buy the parts one by one. For this I wanted to know the average prices of the parts. Firstly I want to buy my RAM’s. For this i will build a model with machine learning algorithms and formulate it. Thus, i will have information about the average price of the ram I want.

## Dataset(Web Scraping)
I need to detailed dataset and a realistic price list for this project. If I researched on web for this dataset, it would be difficult and inadequate. So I've found a shopping site with detailed features and prices about RAMs. I’ve chosed the required pages and started web scraping for it.(I don’t have special api for this website so i scraped manually.)
I’ve used the BeautifulSoap library for this and edited the datas to create a strong and useful dataframe.

