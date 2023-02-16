# Welcome to Data Science Portfolio
##### Author: Ronie Bituin
This repository contains the files for the Portfolio my personal portfolio. 


# Understanding the repository

There are total of **4 Portfolio** folders in this repository and each of them are represented by folders. The dataset for each portfolio are stored under the <i>data</i> folder, in each portfolio folder.

## Discussion
Below will discuss the different Portfolio summary.

### Portfolio 1
The author was provided with the Epinions data collected through a general consumer review web site Epinions.com. Each user on the site can rate and post a review for products (items) and other users would rate the review to show the helpfulness of the review. The main task involves checking irregularities in the dataset and outlier, and treatments of outlier.

### Portfolio 2
The goal of the second analysis task is to train a linear regression models to predict users' ratings towards items. This involves a standard Data Science workflow:
* Exploratory Data Analysis
* Feature Engineering
* Building Models
* Making Predictions
* Evaluating Models

In this task, the author explored the impacts of feature selections and different sizes of training/testing data on the model performance.

### Portfolio 3
In this Portfolio, the task involves continuing the work on the dataset the author used in portfolio 2. But the difference is that the rating column has been changed with like or dislike values. The task is to train classification models to predict whether a user like or dislike an item. 

### Portfolio 4
The goal of the portfolio 4 is to choose preffered dataset and create an analysis out of it. If possible, create a model out of the potential algoritm for the challenge. The author decided to use the dataset from NSW Transportation which are the type of cards being tapped per transportation line. The author did not had his chance to try time-series problem before. He experienced regression problems, classification problems but not time-series challenges. Regression can be considered time-series in some ways but was not tapped particularly on this unit. So he wanted to try a pseudo-time-series challenge.

## Running the notebooks

The author suggests to create a virtual environment before attempting to run the notebook in the local machine. Below are the recommended software ro run the notebooks:
 - Anaconda
 - Visual Studio Code
 -     Install the Jupyter Extension for VS Code

### Steps to create an environment (After installing the Anaconda)
- Open Terminal or Command Prompt 
- `conda create -n data_science_env python=3.9`

### Install required python libraries
- Open Terminal or Command Prompt 
- `conda activate data_science_env`
- `pip install -r /path/to/requirements.txt`

Note that requirements.txt is found in this root repository project.


# Understanding Commits 
To be able for us to easily track our repository progress, the author used appropriate emojis at the start of description/message to determine type of commit.

* :coffee: (coffee) for intial/not important changes
* :100: (100) functions/routes/migrations/etc...
* :notebook: (notebook) readme/comments/documentation
* :sparkles: (sparkles) Added Visualization