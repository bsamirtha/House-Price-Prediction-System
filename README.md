# House-Price-Prediction-System
House price prediction in Bangalore is crucial for informed investment decisions, helping buyers and investors navigate the dynamic real estate market. Accurate predictions support urban planning and policy-making, ensuring sustainable development in one of India's fastest-growing cities.House prices in Bangalore are growing rapidly, driven by the city's booming IT industry and increasing demand for residential properties. The real estate market has seen significant appreciation rates, making it a hotspot for both investors and homebuyers.In this project, we aim to predict the prices of houses in Bengaluru.

# Dataset:  
 https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data 
The dataset, downloaded from Kaggle, contains 13,322 rows and 9 columns.

# Plan of Action

- **Import Libraries**
- **Data Cleaning**
- **Feature Engineering**
- **Dimensionality Reduction**
- **Outlier Detection**
- **One-Hot Encoding**
- **Model Building**
  - Cross-validation model
  - Find the best model using GridSearchCV
  - Test the model on a sample of properties
- **Export the Model**

# Import Libraries
   import pandas as pd
   import numpy as np
   import matplotlib.pyplot as plt

%matplotlib inline 

#Set default figure size
import matplotlib
matplotlib.rcParams["figure.figsize"] = (15, 10)

#Importing the dataset
df1 = pd.read_csv(r"C:\Users\BS . AMIRTHA\Downloads\Bengaluru_House_Data.csv")

#Exploring the dataset
df1.head()





