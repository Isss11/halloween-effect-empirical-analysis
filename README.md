# Can the “Sell in May and Go Away” Strategy Produce Excess Returns in the TSX?

This project was created by Mahir Mehta and Isaiah Sinclair.

## Abstract

“Sell in May and Go Away” (also known as the “Halloween Effect”) is a calendar effect which posits  that the returns in the stock market from the 6-month period of May-October are outperformed by the returns from November-April. 
This research investigates the strength of this effect in the TSX with samples from over 20 years of data across the 4 oldest and largest ETFs (by assets) under management. 
However, we performed most of our research using the XIU ETF, which is well-diversified in the 60 top  companies in the TSX. We perform tests on the models for the difference in return between the two 6-month periods. 
After demonstrating some statistically significant evidence of a Halloween Effect, we construct a Halloween Effect trading strategy, where we buy risk-free assets during May-October, and  invest in the stock market during the November-April period. We compare the results of this model with  the results of a standard buy-and-hold strategy in the XIU ETF, evaluating if there is a statistically 
significant alpha value that can be derived using the Capital Asset Pricing Model (CAPM). We also analyze  the parameter stability of these models.

## Technologies Used

- Python
- Pandas
- Statsmodels
- Jupyter Notebook
- yfinance
- Excel

## Other Skills Demonstrated

- Statistical Analysis
- Financial Econometrics

## Data

The data was downloaded from the Bank of Canada website. 
It has been included in this repository in `tbill_all.csv`.
Some of the intial rows were removed using Excel for easier data cleaning with Pandas.
Please note that the column 'V80691345' represents the 6-month t-bill yield that is used in our empirical research. The data is cleaned by the Python Juypter notebook when it is run.