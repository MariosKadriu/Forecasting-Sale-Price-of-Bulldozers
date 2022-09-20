# Forecasting Sale Price of Bulldozers

## Table of Contents

[Description](https://github.com/MariosKadriu/Forecasting-sale-price-of-bulldozers#-description)
 
[Dataset](https://github.com/MariosKadriu/Forecasting-sale-price-of-bulldozers#-dataset)

[Installation](https://github.com/MariosKadriu/Forecasting-sale-price-of-bulldozers#%EF%B8%8F-installation)

[Exploratory Data Analysis](https://github.com/MariosKadriu/Forecasting-sale-price-of-bulldozers#-exploratory-data-analysis)

[Data Preprocessing](https://github.com/MariosKadriu/Forecasting-sale-price-of-bulldozers#-data-preprocessing)

[Modeling and Evaluation](https://github.com/MariosKadriu/Forecasting-sale-price-of-bulldozers#-modeling-and-evaluation)


## 📝 Description

The above project was implemented with the aim of forecasting the auction sale price for a piece of heavy equipment to create a "blue book" for bulldozers (Featured Prediction Competition of Kaggle in past)

## 📚 Dataset

The used dataset can be found here: https://www.kaggle.com/c/bluebook-for-bulldozers/data

## 🖥️ Installation

### 🛠️ Requirements
* Python >= 3.6
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

### ⚙️ Setup

All of the above packages can be installed from the following commands.

```bash
pip install numpy
pip install pandas
pip install matplotlib
pip install -U scikit-learn

```

## 🔍 Exploratory Data Analysis

### Distribution of sale prices
![image-1](https://user-images.githubusercontent.com/19438003/191294147-4f241a78-bc09-412e-b5d5-74a6b8b262eb.png)

### Distribution of sale prices by year for first 1000 records
![image-2](https://user-images.githubusercontent.com/19438003/191301051-2e904b4d-c901-4ce4-a70c-d3f1eab8f965.png)


## ⏳ Data Preprocessing

* Add datetime parameters (saleYear, saleMonth, saleDay) for saledate column
* Fill the numeric missing rows with median
* Fill categorical missing rows and turn categories into numbers


## 🎯 Modeling and Evaluation

### Models

* Random Forest Regressor

### Evaluation Metrics

* Mean Absolute Error (MAE)
* Root Mean Squared Log Error (RMSLE)
* R2 Score

### Results

#### Scores of a perfect Random Forest Regressor model trained on all data
![image-3](https://user-images.githubusercontent.com/19438003/191307744-1e1c18ba-863a-43ef-9038-908d5dd1b8d7.jpg)

#### Format the predictions in the same format that Kaggle seeks
![image-4](https://user-images.githubusercontent.com/19438003/191306135-766809cd-1bfe-4473-8127-d318348518db.jpg)

#### Feature Importance
![image-5](https://user-images.githubusercontent.com/19438003/191306926-df2edf7c-e812-4951-a2ff-df008ca65aff.png)
