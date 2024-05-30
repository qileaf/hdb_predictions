# :house_with_garden: Shokuniwa RealEstate Insights :house_with_garden:
##### Unveiling Key Drivers of HDB Resale Prices in Singapore for enhanced data-driven decision making

### Problem Statement
While Shokuniwa RealEstate Insights Pte Ltd specializes in new developments, they are currently looking to expand their influence in the Singapore HDB resale market. Hence, the company is looking for a viable solution to predict market prices for resale HDB apartments, which will allow their agents to have an estimate of the resale prices for their current listings and price them feasibly.

### Objectives:
1. Identify the most significant features influencing HDB resale prices: Through rigorous feature selection techniques, pinpoint the key factors driving housing prices.
2. Develop a highly accurate regression model to predict resale prices. The goal of our data prediction model is to empower the client Company's real estate agents with swift and efficient, data-driven, and highly reliable resale price predictions.

### Data Dictionary

As there are over 70 features, the data dictionary is stored separately in data_dictionary.txt

### Installation

***Cloning the repository***

`gh repo clone qileaf/hdb_predictions`

or via html:

`https://github.com/qileaf/hdb_predictions.git`

***Dependencies***

Install the dependencies by opening your terminal in the project folder and run:

`pip install -r requirements.txt`

After installation, you should then be able to run the code smoothly! :smile:

***.ipynb***

The project file is in .ipynb format and was created in VS Code and Jupyter Notebook :book:

### Annex

***Datasets***

'train.csv': https://www.kaggle.com/competitions/dsi-sg-project-2-regression-challenge-hdb-price/data
Contains 75 features with resale prices of over 150,000 data points, between 2012-2021. To be used as training set for the model.

'test.csv': https://www.kaggle.com/competitions/dsi-sg-project-2-regression-challenge-hdb-price/data
Contains 75 features without the resale prices of close to 17,000 data points for prediction.