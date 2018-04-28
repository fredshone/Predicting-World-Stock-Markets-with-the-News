# Predicting-World-Stock-Markets-with-the-News
Jupyter workbook using a geolocating dictionary and sentiment analysis of Reuters Headlines to predict Global Stock Market Variation.

Work in progress (although it works fine if you have access to the University College London SQL servers) - currently planning to update for 6 years of data and providing some csv data dumps.

### Methods
1. **Sentiment Analysis** using Textblob package
2. **Geolocating** using a bespoke dictionary of Country Names, Cites, States and Nationalities
### Novel Features
1. Headlines tagged with multiple locations are duplicated accordingly
2. Neighbour network affects are considered
### Problems
1. Currently no check for duplicated (re published) headlines
2. Sentiment analysis is basic
3. Requires my SQL server

**Spoiler Alert:** There doesn't look to be a statistically significant link.
