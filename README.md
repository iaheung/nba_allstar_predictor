[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/txrjyOPN)
# Final Project title

In this project, we will create two models to predict whether an NBA player makes an all-star nomination based on seasonal statistical performances.

A package for data scraping is required to be installed for `data_extraction.py`.

Install the package using pip:

```
pip install basketball-reference-scraper
```

Folder structure:
 - `doc/` Project instructions
 - `evaluate/` Confusion matrices, evaluation metrics
 - `handins/` Data exploration slides, project report PDF
 - `notebooks/` Notebooks for data visualization, inital model testing
 - `processed_data` Raw data organized for visualization and further transformation and processing
 - `raw_data` Raw scraped data
 - `scripts` Scripts to extract and transform data, run models
 - `training_data` Processed training and test split data

### Instructions
First extract data from basketball reference by using a data scraping script, `data_extraction.py`. It takes around 6 hours for all the data to run. \
Prepare data for model training by running `data_processing.py` and `train_test_split.py`\
Train models and obtain evaluation metrics and confusion matrices on `decision_trees.py` and `mlpnn.py`. Both files are independent of each other, code does not depend on the other file\

### Important Dates:
 - **Data exploration presentation:** Thursday, April 25 in class
 - **Project Deadline:** End of *your* finals: May 6 (seniors) May 8 (others)
