# Stock Markets Analytics Zoomcamp - Module 1 Homework

**Student:** Santiago Parada  
**Course:** Stock Markets Analytics Zoomcamp

This project contains the Module 1 homework notebook. It analyzes index additions, international index returns, S&P 500 corrections, and Amazon earnings surprises, and proposes an electricity-market analytics project for Colombia.

## Questions 1-6 Summary

1. **S&P 500 additions:** Identifies the year with the most additions among current constituents and counts companies that have been in the index for more than 20 years.
2. **International index returns:** Compares 2026 YTD returns for 10 international indexes against the S&P 500, with additional 3-, 5-, and 10-year comparisons.
3. **S&P 500 corrections:** Finds corrections of at least 5% and summarizes drawdowns and their durations.
4. **Amazon earnings surprises:** Measures the two-day price reaction after positive AMZN earnings surprises and estimates the correlation with surprise magnitude.
5. **Capstone proposal:** Proposes EnergyRisk Colombia, a next-day electricity spot-price forecasting and high-volatility detection project.
6. **Additional metrics:** Explores Colombian electricity spot price, real demand, useful reservoir volume, and hydrological energy inflows.

## EnergyRisk Colombia Proposal

EnergyRisk Colombia would forecast the next day's average national electricity spot price in COP/kWh and identify unusually high-volatility periods. The project would use public XM Sinergox data, including recent prices, electricity demand, useful reservoir volume, and hydrological inflows. Baselines such as the previous day's price and a seven-day moving average could be compared with linear and tree-based regression models using chronological validation.

## Data Sources

- [Wikipedia S&P 500 companies](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies)
- [Yahoo Finance](https://finance.yahoo.com/)
- [XM Sinergox](https://sinergox.xm.com.co/)

## Opening the Notebook

Open `homework1_santiago_parada_v2.ipynb` with [Jupyter Notebook](https://jupyter.org/) or Visual Studio Code with the Jupyter extension. Install the Python dependencies listed in the notebook setup cell before running it, and run the cells from top to bottom.

## Disclaimer

This project is educational and is not financial advice.
