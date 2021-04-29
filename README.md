# Financial Time-Series Forecasting Challenge
*30412 - Machine Learning*

*Università Commerciale L. Bocconi*

Piercesare Fagioli,
Tommaso Ghisini,
Francesca Malfiore,
Silvia Romanato,
Alessandro Sinai,
Mattia Stilinovic.

#### Rules:
- The data consist of time series, splitted in a training and a test set;
- The training set contains both inputs and outputs. The inputs are the returns for the first 50 time steps and the outputs that are the returns of the time series for the 51-st time step.
- The test set contains only the inputs.
- Each time series has its first 50 values indexed by columns from 0 to 49. There is an additional column called ‘w’, which you can disregard.

#### Final Submission consists of:
- The predictions on the test set, to be uploaded on the [Bocconi Data Science Challenges platform](http://data-science-challenges.unibocconi.it)
- A short (!) report detailing your approach, 2 pages maximum
- A notebook with code that reproduces the predictions on the
test set, starting from the training set. This should include hyperparameter optimization.

-----
**The submission deadline is next _Wednesday, the 28th, at 3:00 pm CET_.**

-----

#### File Structure:
- `f1.ipynb` -> Data Import and Preparation + Basic Linear Regression
- `f2.ipynb` -> Adds Supported Vector Machine + LSTM (not working correctly in this version)
- `f4.ipynb` -> Minor changes to `f1.ipynb` + XGBoost and GridSearch to optimize hyperparameters
- `/data` -> contains train and test datasets
- `/submissions` -> contains submissions made on the platform
