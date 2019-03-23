# Machine-Learning-for-Investing

parsing_finance_data.py parses through a bunch of html files which are ordered in time and in a corresponding company ticker file i.e Apple tickis "AAPL"

We are able to get the key statistics from the past Yahoo Finance html files for each company between 28/01/2004 to 09/06/2013

finance_modelling.py creates a support vector machine classifier that is able to predict if a company should be bought or sold based upon if a company is a outperformer or underperformer.
The accuracy score is subsequently measured via the testing set.
