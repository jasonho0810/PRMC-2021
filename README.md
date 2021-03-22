# PRMIA Risk Management Challenge 2021 - The Big Four
This is a dashboard and summary report derived from the National Australia Bank case. The dashboard contains risk and performance metrics of an options market making desk. We have:
1)	Defined a portfolio of financial instruments to simulate the NAB case
2)	Identified the appropriate performance and risk metrics to monitor
3)	Created an interactive dashboard with key parameters and visuals

## Instructions:
1. You will need to first obtain a source of traded options transaction data.
2. Then clean the data and compute Greeks and implied volatilities calculations using the Python script `Data cleaning and calculations.ipynb`. This will generate a `database_TB_Ready.csv` file.
3. Launch Tableau and load `database_TB_Ready.csv` file and `VaR and ES.csv` file.
More detailed instructions and usage can be found [here.](https://play.library.utoronto.ca/1f3ded59e30b3500e4b24100fe3ba7d9)

## Installations:
#### Python
```python
pip3 install -r requirements.txt
```
- matplotlib
- pandas
- numpy
- tqdm
- statsmodels
- py_vollib
- warnings

#### Tableau
- Tableau Desktop v2020.4 (older versions may work)

## File Description:
- `AUDUSD=X.csv` - Data from Yahoo Finance on USD/AUD spot exchange rates for February 2021. We use the *Adj Close* as the spot exchange rate for calculations of implied volatilities and Greeks.
- `Data cleaning and calculations.ipynb` - All data processing and calculations for the example data are contained within this Jupyter notebook.
- `database_TB.csv` - Cleaned data of one-month USD/AUD FX traded options transaction for February 2021.
- `VaR and ES.csv` - Simulation data for VaR and ES calculations.

## Licensing, Authors, and Acknowledgements:
[MIT License](https://github.com/jasonho0810/PRMC-2021/blob/main/LICENSE)
