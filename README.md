<p align="center"><img src="https://github.com/nascimentorapha/term-paper/blob/master/.github/title.JPG"/></p>

# Term Paper - Computer Engineer


---

## :globe_with_meridians: Technologies
- [Python](https://www.python.org/)
- [Google Colab](https://colab.research.google.com/)
- [Alpha Vantage API](https://www.alphavantage.co/)
- [Twitter API](https://developer.twitter.com/)
- [Pandas Lib](https://pandas.pydata.org/)
- [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment)
- [Scikit-Learn](https://scikit-learn.org/) 
- [TensorFlow](https://www.tensorflow.org/)

---
## :scroll: Resume

The present works proposes analyze and study through Artificial Intelligence the relationship between the new's sentiment and the stock exchange variation value 

---

## :hammer_and_wrench: Prerequisites
We suggest you to use Google Colab to run the codes and ajust to companys that you prefer 

First step

```bash
# Clone this repository
$ git clone https://github.com/nascimentorapha/term-paper.git
```
Install APIs and import libs

```bash
#Alpha Vantage API
!pip install alpha_vantage

# import libraries
from alpha_vantage.timeseries import TimeSeries
import matplotlib.pyplot as plt
import pandas as pd
from pandas import DataFrame
from sklearn.preprocessing import StandardScaler
from sklearn.linear_model import LinearRegression
import tensorflow as tf

# Run app
$ npm start

```

--- 

## :information_source: How To Use

* **1 Search Intraday** - In path codes, run **1_get-intraday.ipynb** to search the intraday company that you want and change the company code on Stock Market. E.g. Petrobras = PBR. Here we'll export the intraday data to csv.

* **2 Search Tweets** - Search tweets with Twitter API. We suggest to use the code made by Jefferson Henrique on this link (https://github.com/Jefferson-Henrique/GetOldTweets-python). We'll export to a csv here too;

* **3 Proccess data** - Run **3_adjustTweetsDatetime.ipynb** to properly process tweet data for later concatenate with intraday;

* **4 Sentiment Analyze** - Run **4_vader_analyzer.ipynb** to read and process tweets that we get on **step 3**

* **5 Start Linear Regression** - In this step we'll process 