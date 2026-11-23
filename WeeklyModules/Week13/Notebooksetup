"""
Notebooksetup.py
Common imports and display settings for MSSP 607 notebooks.
Run at the top of a notebook with: %run Notebooksetup.py
"""

import datetime

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import yfinance as yf

# Show floats with 2 decimal places instead of scientific notation
pd.set_option('display.float_format', lambda x: '%.2f' % x)

# Show all columns when printing wide data frames
pd.set_option('display.max_columns', None)

# Consistent plot style across the notebook
sns.set_theme(style='whitegrid')
plt.rcParams['figure.figsize'] = (10, 6)

print('Notebook setup complete: pandas, numpy, seaborn, matplotlib, yfinance, datetime loaded.')
