# Stock Price Prediction using ML(Machine Learning)

In this project we aim at analizing and forecasting the stock price of Apple as well as preparing and cleaning other company's stocks for fitting them to the model in the future.

## About the Project

Companies that become public, which means those which the general puclic can invest onto, are divided in small fractions called shares. Those shares are available for purchase in the form of investment, and the price of each share varies depending on the revenue of said company, the amount of shares at the public disposal, the stability of the companie's finances, industry trends and so on... 
As more people get into investing their money, it is beneficial for them to have an certain degree of confidence on where they are putting their investment. That`s where this data forecasting project comes in: it aims to create a model that will give people some peace of mind and confidence that they are making the best possible decision with their capital. 


## Getting Started

The overall workflow to use machine learning to make stocks prediction is as follows:

1. Acquire historical fundamental data – these are the *features* or *predictors*
2. Acquire historical stock price data – this is will make up the dependent variable, or label (what we are trying to predict).
3. Preprocess data
4. Use a machine learning model to learn from the data
5. Predict the forecasted priced and compare to original prices
6. Measure the accuracy of the model

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
```

## Usage

This project was developed on Jupyter Notebook. To use it simply click on 'Copy and Edit' on GitHub or download the file. Once opened you can work freely on the cells.
Due to the fact that I've worked on a customized environment, if it comes a time when you can't install a package or library, simply use 'pip install' to get the package installed to your environment. 

## Contributing

#### 1. Reporting Bugs

If you encounter a bug or unexpected behavior, please help by providing detailed information:

- **Check Existing Issues:** Before reporting a new issue, check if a similar one already exists in the [Issues](link-to-issues) section.

- **Bug Report Template:** Use the [Bug Report Template](link-to-bug-template) to create a detailed bug report. Include steps to reproduce, expected behavior, and any relevant screenshots or error messages.

#### 2. Suggesting Enhancements

Have an idea for a new feature or improvement? I'd love to hear it! Follow these steps:

- **Check Existing Features:** Ensure your suggestion hasn't been proposed before by checking the [Issues](link-to-issues) section.

- **Feature Request Template:** Use the [Feature Request Template](link-to-feature-template) to describe your proposed enhancement. Be clear about the problem it solves and any suggested implementation details.

#### 3. Contributing Code

If you're interested in contributing code changes, please follow these steps:

- **Fork the Repository:** Fork the project to your GitHub account.

- **Create a Branch:** Create a new branch for your changes. Use a descriptive branch name related to the feature or bug fix.

- **Make Changes:** Implement your changes following the project's coding style and conventions.

- **Write Tests:** If applicable, include tests for your changes.

- **Create a Pull Request:** Submit a pull request to the [main repository](link-to-main-repo). Ensure you provide a clear description of your changes and reference any related issues.

### Code Style and Guidelines

To maintain a consistent codebase, follow these guidelines:

- Adhere to the [coding style guide](link-to-style-guide) for the project.

- Write clear and concise commit messages.

- Include comments where necessary, especially in complex or critical sections.

### Code Review Process

All code changes go through a review process before being merged. Be open to feedback and address any concerns raised during the review.

Thank you for your contributions! 🚀

## Acknowledgements

I'd like to agknowledge the help and contribution of the mentors at Brainstation, Borna Ghotbi and Nitin Bhandari, that help me out through the development of this project.

Thank you
