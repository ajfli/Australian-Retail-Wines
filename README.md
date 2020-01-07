# Predicting Retail Wine Prices
# Introduction
Continuing on from the Australian Vineyard project, this notebook presents a comprehensive analysis of features associated with retail wine prices. Wines vary considerably on myriad features, including variety, vintage, body, and region of origin. Businesses may wish to understand the extent to which these factors influence the pricing of their competitor's products, as this could inform their product pricing strategies.

The aim of this project is to determine these relationships between wine features and retail price, with a particular focus on the popular wine retailer Dan Murphy's.

# Results
An XGBoost regressor model was able to explain 88% of the variance in wine price on a test set. This result is quite a good result given that we have not examined other market dynamics influencing retail price, including place of business and buyer demographics. The most important feature for prediction was Langton's classification, followed by closure type, variety, brand name, and vintage. Watering information taken from an Australian Bureau of Statistics (ABS) dataset showed no relationship with price, suggesting that these factors have little influence on Dan Murphy's product pricing strategy.

# Conclusion
Overall, findings shed light on the features associated with Dan Murphy's retail wine prices, which may inform the future pricing strategy of a competitor business. Future models could incorporate the overall development costs of each wine, as this would provide a more complete picture of Dan Murphy's pricing scheme. Teasing apart price markups due to 1) development costs, and 2) wine characteristics (e.g. corkage, vintage) will prove difficult, but should inspire ongoing work.
