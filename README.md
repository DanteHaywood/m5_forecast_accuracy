# m5_forecast_accuracy
 Repository for submission to the M5 Forecast Competition hosted on Kaggle. The objective of the competition is to spur development on time series forecasting. The data for the competition comprise of 30,490 timeseries of sales of products across ten Walmart stores in 3 U.S. states. The notebook includes benchmark models listed in the competitor guide.

**Table of contents**

* **M5 Forecast Competition - Accuracy**
  * Credits
* **Section 1: Load Data and Benchmark**
   * Load data and set data types
   * Please Credit dante.haywood at gmail dot com for the rest of the notebook
* **Section 2: Benchmark models**
   * Moving Average
   * Exponential Smoothing
   * Double Exponential Smoothing
   * Croston's Method and Variants
   * ARIMA and Variants
   * Prediction
   * Note on timing
   * Plot the trained time series models
   * Loop through all series and record the in sample fits, forecast, and RMSSE
   * Read random blocks of data back in
   * Plot the output of opt_models_wrapper
* **Section 3: RNN-Gated Recurrent Unit**
   * Train and Test set
   * TimeseriesGenerator
   * Create time series sequences and target
   * Create and fit model
   * Callback for logging loss history
   * Train RNN while periodically saving progress
