# fx-pair-strategy

## Background
A popular class of strategies in the foreign exchange (FX) markets involves time-series momentum.  It is based on buying the currency pair that shows recent positive returns and selling those that demonstrate recent negative returns.

## Data
Cambridge Square Capital LP (Boston) provided a pickled dataframe of USDJPY (Japanese yen) and USDMXN (Mexican peso) exchange rates.

## Recommendation
A memo to Cambridge Square Capital recommends a simple (5, 20) moving average rule assuming active management of the pairs on a monthly basis.  The supporting analysis is included in the Jupyter notebook.

All analysis was completed in Python 2.7 using Pandas.  To run, create a `conda` environment and install the requirements:

```
conda install -c synthicity prettytable
```
