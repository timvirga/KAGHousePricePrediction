KAGHousePricePrediction
Using ML and Data Science techniques to predict house prices https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

1. (WINDOWS) install WSL - Ubuntu
* Setup vscode and install/import requirements.txt

2. Project initialisation
Clone github repo

* In git bash terminal: git clone https://github.com/timvirga/KAGHousePricePrediction.git
* Create virtual environment
* Install requirements.txt (pip install -r requirements.txt)
    * if you get an error installing tfdf, try pip3 install tensorflow_decision_forests

### NB1 represents the base notebook with foundational tf-df model code to run the model on the dataset without any feature engineering or data cleaning. This is the starting point for the project.

### NB2 represents the notebook with some basic feature engineering and data cleaning, with a focus on refining the data to be more suited to the tf-df model. This is the second step in the project.