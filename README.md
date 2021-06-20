# Bitcoin Opportunities - Bitstamp and Coinbase

This is a Pandas analysis application in a Jupyter Notebook that allows visualization of Bitcoin on two trading exchanges: Bitstamp and Coinbase.  The analyis runs from January 1, 2018 through March 31, 2018.  There are three specific dates of focus: January 29, February 10 and March 25.  As the analysis shows, the profitable exchange opportunities were concentrated to the end of January and then phased out as time progressed.

---

## Technologies

This analysis is made possible by the following packages:

*[Pandas] (https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)

*[Pathlib] (https://realpython.com/python-pathlib/)

*[%matplotlib inline] - (https://matplotlib.org/)

---

## Installation Guide

Before running the analysis application, first install the following:

'''pandas
    import pandas as pd
    from pathlib import Path
    %matplotlib inline
'''

---

# Usage

To use the analysis applicaiton, clone the repository and run the crypto_arbitrage.ipynp in Jupyter Lab.  Please note, the functions removing the $ from the "Close" column and updating the "Close" column to a float, must be run in order of the application to execute properly.  The dates in the analysis are references as "Early = January 29, 2018", "Middle = February 10, 2018" and "Late = March 25, 2018."

![Bitstamp v Coinbase Visualization](Starter_Code/Bitstamp v Coinbase Jan-Mar 2108.png)
---

## Contributors

This analysis has been created by Abolla04 with the assistance of "Seth the Tutor" and the FinTech TAs.

---

## Licence

TIM
