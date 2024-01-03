# Stock Price Prediction using ML(Machine Learning)

In this project we aim at analizing and forecasting the stock price of some of the most prominent companies in the Stock Market. They are: Apple; Amazon; Google; Netflix; Nvidia and Tesla.

## About

Companies that become public, which means those which the general puclic can invest onto, are divided in small fractions called shares. Those shares are available for purchase in the form of investment, and the price of each share varies depending on the revenue of said company, the amount of shares at the public disposal, the stability of the companie's finances, industry trends and so on... 
As more people get into investing their money, it is beneficial for them to have an certain degree of confidence on where they are putting their investment. That`s where this data forecasting project comes in: it aims to create a model that will give people some peace of mind and confidence that they are making the best possible decision with their capital. 

## Getting Started

The overall workflow to use machine learning to make stocks prediction is as follows:

1. Acquire historical fundamental data – these are the *features* or *predictors*
2. Acquire historical stock price data – this is will make up the dependent variable, or label (what we are trying to predict).
3. Preprocess data
4. Use a machine learning model to learn from the data
5. Backtest the performance of the machine learning model
6. Acquire current fundamental data
7. Generate predictions from current fundamental data

This is a very generalised overview, but in principle this is all you need to build a fundamentals-based ML stock predictor.

### Prerequisites

This project uses python 3.6, and the common data science libraries `pandas`, `numpy`, `matplotlib`, `seaborn` and `scikit-learn`. A full list of requirements is included bellow. To install all of the requirements at once, run the following code in terminal:
```bash
# import libraries
import numpy as np
import pandas as pd

# plotting
import plotly.express as px
from plotly.subplots import make_subplots
import plotly.graph_objs as go
import matplotlib.pyplot as plt
import seaborn as sns

# stats
from statsmodels.api import tsa # time series analysis
import statsmodels.api as sm
bash





