# Collective Investment Funds Analysis for Colombia
The objective of this project is to analyze the performance of the different options of Collective Investment Funds that are available right now in Colombia for small individual investors, and compare them to the ETF alternative. 

Thus, the returns and risk are analized, compared between them, and finally compared with two ETFs. The analysis will be only  done for the CIF([ESP](https://www.asofiduciarias.org.co/educacion-financiera/fondos-de-inversion-colectiva/) [ENG](https://www.occ.treas.gov/topics/supervision-and-examination/capital-markets/asset-management/collective-investment-funds/index-collective-investment-funds.html)) registered in "*Asociación de Fiduciarias de Colombia*", which is where the data is extracted. 

The two ETFs analyzed are the  [SPY](https://en.wikipedia.org/wiki/SPDR_S%26P_500_Trust_ETF) and the [GXG](https://www.globalxetfs.com/funds/gxg/). 



## Documentation
For information about the Collective Investment Funds analyzed, visit the [AFC page](https://www.asofiduciarias.org.co). This is the source for the data (which is in the Excel file in the repo). The differences among the CIF categories analyzed in the project are described [here](https://sificcolombia.lvaindices.com/frontend/documentos/20200520%20-%20Metodología%20Categorización%20FICs%20Versión%205.0%20(Final)1%20(1).pdf). The period of analysis is the daily performance from 2017-2020. 

The data of the ETFs is extracted from the Yahoo Finance [API](https://pypi.org/project/yfinance/).

The Jupyter Notebook is organized as follows:

1. Introduction of the project
2. Objective of the project
3. Data Understanding
    1. Collective Investment Funds analysis
    2. ETFs analysis
    3. Comparison
4. Relation between volatility and returns

## Tools and Software Used
The whole project was done in Jupyter Lab (v. 2.2.6)

The Python libraries used are:
+ [Pandas](https://pandas.pydata.org): v.1.1.3
+ [Numpy](https://numpy.org): v.1.19.2
+ [Matplotlib](https://matplotlib.org): v.0.23.2
+ [Scikit-Learn](https://scikit-learn.org/stable/): v.3.3.2
+ [Yahoo Finance API](https://pypi.org/project/yfinance): v.0.1.54

## Acknowledgements

Thanks to [Coursera](https://www.coursera.org) [Edx](https://www.edx.org) and [Udacity](https://www.coursera.org) for spreading great quality education online. Without their content this couldn't be possible. 
