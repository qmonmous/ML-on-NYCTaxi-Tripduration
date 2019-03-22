# NYC-taxi-trip-duration-predictions

This is my very first predictions, made for a Kaggle competition that you can find [here](https://www.kaggle.com/c/nyc-taxi-trip-duration). 
In this notebook, I go through the complete Machine Learning workflow. I tried to optimize both RandomForest and LightGBM models, with a respective error of RMSLE 0,39 and 0,37.
You can find my work and score [here](https://www.kaggle.com/quentinmonmousseau/predictions-using-randomforestregressor) or simply have a look at the [notebook](https://github.com/qmonmous/NYC-taxi-trip-duration-predictions/blob/master/predictions.ipynb) I put in this repository.

---

### About the competition

The competition dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this playground competition. Based on individual trip attributes, participants should **predict the duration of each trip in the test set.**

### File descriptions

**train.csv** - the training set (contains 1458644 trip records)
**test.csv** - the testing set (contains 625134 trip records)
**submission.csv** - the submission file in the required format