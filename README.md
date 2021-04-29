# Financial Time-Series Forecasting Challenge
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/googlecolab/colabtools/blob/master/TimeSeries_Forecasting.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tommasoghisini/FinancialTimeSeriesForecasting/HEAD?filepath=TimeSeries_Forecasting.ipynb)

### **30412 - Machine Learning @ Università Commerciale L. Bocconi**

2021 Data Science Challenge for the BEMACS course

### Authors
- Piercesare Fagioli
- Tommaso Ghisini
- Francesca Malfiore
- Silvia Romanato
- Alessandro Sinai
- Mattia Stilinovic


### Rules
- The data consist of time series, splitted in a training and a test set;
- The training set contains both inputs and outputs. The inputs are the returns for the first 50 time steps and the outputs that are the returns of the time series for the 51-st time step.
- The test set contains only the inputs.
- Each time series has its first 50 values indexed by columns from 0 to 49. There is an additional column called ‘w’, which you can disregard.

### Final Submission consists of
- The predictions on the test set, to be uploaded on the [Bocconi Data Science Challenges platform](http://data-science-challenges.unibocconi.it)
- A short (!) report detailing your approach, 2 pages maximum
- A notebook with code that reproduces the predictions on the
test set, starting from the training set. This should include hyperparameter optimization.

-----
**The submission deadline is _Wednesday 28th of April 2021 at 3:00 pm CET_.**

-----

### File Structure
```
Financial Time Series
|
+-- Timeseries_forecasting.ipynb
|
+-- data -> contains train and test datasets
|   |
|   +-- test.csv
|   +-- train.csv 
|
+-- old -> contains old versions
|   |
|   +--f1.ipynb -> data import and preparation + basic linear regression
|   +--f2.ipynb -> adds Supported Vector Machine + LSTM (not working correctly in this version)
|   +--f3.ipynb -> implements LSTM (working version) w/ cross-validation and GridSearch
|   +--f4.ipynb -> minor changes to `f1.ipynb` + XGBoost and GridSearch to optimize hyperparameters
|
+-- README.md
|
+-- Report.pdf

```
