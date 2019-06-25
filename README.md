# WeRateDogs Twitter Archive Data Wrangling Project

In this project, the dataset I analyze is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). This twitter account rates people's dogs with ratings on denominator of 10 along with comments. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of tweets from August 1, 2017.

<sub>This project is provided by Udacity Data Analyst Nano Degree.</sub>

## Motivation

The objective of this project is wrangling WeRateDog Twitter Archive data to draw interesting and trustworthy analyses and visualizations . The main focus on my project is performing data wrangling from a variety of sources and in variety of formats, in the process of gathering, accessing and cleaning using Python and its libiraries. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
python3   -m pip install Package_name
```

## Usage

```python
import pandas as pd
import numpy as np
import requests
import tweepy
import json
import re
import matplotlib.pyplot as plt
import seaborn as sb
import statsmodels.api as sm
from scipy.stats.stats import pearsonr
%matplotlib inline
```

## Features

- Gathering datasets from three sources.
- Accessing data with nine quality issues and three tidiness issues defined.
- Cleaning data in ten steps. Each step performing Define, Code and Test in order.
- Storing final clean dataframe in csv file.
- Analyzing data building with a Linear Regression model and seven visualization plots.
- Summarizing conclusions with interpretable results.
- Discussing on limitations to be further studied.

## Author
This project was completed by Chloe Xue. 

## License
[MIT](https://choosealicense.com/licenses/mit/)