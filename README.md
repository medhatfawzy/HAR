# Human Activity Recognition
In this repository, we present the work done on the HAR dataset.
There're four notebook for each stage in the development.

## 1. Aggregating Data
In this notebook, we concatenate the data from multiple files and create a single dataframe to combine them all. The dataframe is then saved into a parquet file to speed up any reading operations later in the pipeline.

While aggregating the files, we realized that there are duplicate column names. We modified the original file that had the names of the features to fix this issue.

## 2. EDA
In this notebook, we perform some EDA on the dataset to check for imbalance and biases and also to get a deeper look into the data.

## 3. Feature Engineering
In this notebook, we try different feature reduction and selection techniques due to the large amount of features we have.

## 4. Models
In this notebook, we test different models and ML algorithms on  the data and then we select the best performing model.
