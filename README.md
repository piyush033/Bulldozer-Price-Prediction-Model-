# Time-Series-Data-Project

# Problem Statement
Predit the future sale price of a bulldozer by its charactersticsand previous examples(how much similar bulldozer have been sold.)

* [Main Code](https://github.com/piyush033/Time-Series-Data-Project/blob/main/Bulldozer-Price-Regression.ipynb) 

# Table of Content
* [Problem Statement](https://github.com/piyush033/Time-Series-Data-Project/blob/main/README.md#problem-statement)
* [Dataset Used](https://github.com/piyush033/Time-Series-Data-Project/blob/main/README.md#dataset-used)  
* [Frameworks Used](https://github.com/piyush033/Time-Series-Data-Project#frameworks-used)
* [Bulldozer Data Dictionary](https://github.com/piyush033/Time-Series-Data-Project#bulldozer-data-dictionary)
* [Model Visualizations](https://github.com/piyush033/Time-Series-Data-Project#model-visualizations)

# Dataset Used 
The original data come from [Kaggle Blue Box for Bulldozers](https://www.kaggle.com/competitions/bluebook-for-bulldozers/data) prediction competition.

You can find this also in my repository: [My Repository](https://github.com/piyush033/Time-Series-Data-Project/tree/main/Data) 

# Frameworks Used

* [Numpy](https://numpy.org/doc/)
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
* [Scikit-Learn](https://scikit-learn.org/stable/)
* [Matplotlib](https://matplotlib.org/stable/index.html)
* [Seaborn](https://seaborn.pydata.org/)

# Bulldozer Data Dictionary

The data for this competition is split into three parts:

* Train.csv is the training set, which contains data through the end of 2011.
* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

The key fields are in train.csv are:

* SalesID: the uniue identifier of the sale
* MachineID: the unique identifier of a machine.  A machine can be sold multiple times
* saleprice: what the machine sold for at auction (only provided in train.csv)
* saledate: the date of the sale

There are several fields towards the end of the file on the different options a machine can have.  The descriptions all start with "machine configuration" in the data dictionary.  Some product types do not have a particular option, so all the records for that option variable will be null for that product type.  Also, some sources do not provide good option and/or hours data.

The machine_appendix.csv file contains the correct year manufactured for a given machine along with the make, model, and product class details. There is one machine id for every machine in all the competition datasets (training, evaluation, etc.).

# Model Visualizations

Data:

![Screenshot 2022-07-26 121038](https://user-images.githubusercontent.com/100412728/180940789-dfc642ba-9b1d-48c3-a5ce-89dce913f067.png)

![Screenshot 2022-07-26 121120](https://user-images.githubusercontent.com/100412728/180940829-2dba87b3-3823-4821-b68e-16717fb5134f.png)

![Screenshot 2022-07-26 121147](https://user-images.githubusercontent.com/100412728/180940838-e70f515f-0d86-4a80-ac49-81143ee0b050.png)
