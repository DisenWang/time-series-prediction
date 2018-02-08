# Intro
This tutorial is originally published by William Koehrsen at https://towardsdatascience.com/time-series-analysis-in-python-an-introduction-70d5a5b1d52a

# Setup
for Mac:
Install python 3 using Homebrew: `$ brew install python3`

Install python3 virtualenv: `virtualenv -p python3 venv`

Activate it: `source venv/bin/activate`

Install packages: `pip3 install --upgrade jupyter matplotlib numpy pandas scipy scikit-learn fbprophet`

Run Jupyter: `jupyter notebook`

# Accessing financial data
we will access financial data using the Quandl library. Please go to https://www.quandl.com/tools/python and register to get your api_key, which will be needed to pull data from the quandl financial library.


### About the DeprecationWarning:
Your editor may report warning when you try to run the code, this is because the update of packages. You can ignore those warnings for now.
