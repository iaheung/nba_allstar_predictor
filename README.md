# NBA All Star Predictor

This predictor aims to predict whether an NBA player makes an all-star nomination based on seasonal statistical performances.

A package for data scraping is required to be installed for `data_extraction.py`.

Install the package using pip:

```
pip install basketball-reference-scraper
```

Folder structure:
 - `evaluate` Performance metrics and confusion matrices of various models
 - `scripts` Scripts to extract and transform data, run models
 - `training_data` Processed training and test split data

### Instructions
First extract data from basketball reference by using a data scraping script, `data_extraction.py`. It takes around 6 hours for all the data to run. \
Prepare data for model training by running `data_processing.py` and `train_test_split.py`. Folders containing the data will be created.\
Train models and obtain evaluation metrics and confusion matrices on `decision_trees.py` and `mlpnn.py`. Both files are independent of each other, code does not depend on the other file\
