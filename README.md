# Flight Price Prediction Project

This project aims to predict flight ticket prices based on various features such as airline, date of journey, source, destination, and other flight-related factors. The goal is to analyze these features and build a model that can accurately predict flight prices.

## Project Overview

Flight prices are influenced by numerous factors, including airline type, time of travel, and class. This project explores these factors and uses machine learning techniques to develop a predictive model that can estimate flight prices. The notebook includes detailed data exploration, preprocessing, model training, and evaluation.

## Key Features of the Project

1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
2. **Exploratory Data Analysis (EDA)**: Investigating the relationships between different features and flight prices.
3. **Feature Engineering**: Extracting useful information, such as day, month, and duration from existing features.
4. **Model Building**: Training machine learning models to predict flight prices.
5. **Model Evaluation**: Using metrics like Mean Absolute Error (MAE) and R² score to evaluate model performance.

## Datasets

This project uses two datasets:

- **Data_Train.xlsx**: The training dataset containing historical data of flight prices and other relevant features.
- **Data_Test.xlsx**: The test dataset for evaluating the model's performance on unseen data.

### Key Columns in the Dataset

- **Airline**: The airline operating the flight.
- **Date_of_Journey**: The date of the journey.
- **Source**: The starting point of the journey.
- **Destination**: The endpoint of the journey.
- **Route**: The route taken by the flight.
- **Duration**: Total flight duration.
- **Total_Stops**: Number of stops between source and destination.
- **Price**: Ticket price (only available in the training dataset).

## Files in This Repository

- **Flight-Prediction.ipynb**: The main notebook for data analysis, model training, and evaluation.
- **Data_Train.xlsx**: The training dataset.
- **Data_Test.xlsx**: The testing dataset.

## Installation and Setup

To run this project, you will need:

- Python 3.x
- Jupyter Notebook
- Required libraries (install using `pip install -r requirements.txt` if a requirements file is provided)

### Required Libraries

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Process and Analysis Steps

The following steps were followed in the analysis:

1. **Data Loading and Cleaning**:
   - Load the datasets and check for missing values.
   - Handle missing values and encode categorical variables.
   
2. **Exploratory Data Analysis**:
   - Generate summary statistics for key variables.
   - Visualize the distribution of features like price, duration, and total stops.
   
3. **Feature Engineering**:
   - Extract additional features such as day, month, and duration from date and time fields.
   - Convert categorical features (e.g., airline, source, destination) to numerical representations.

4. **Model Building**:
   - Train several machine learning models such as Linear Regression, Decision Tree, and Random Forest to predict flight prices.
   
5. **Model Evaluation**:
   - Evaluate the models using Mean Absolute Error (MAE) and R² score to determine the best-performing model.

## Results and Insights

The analysis revealed several insights:

- **Price Factors**: Certain airlines, shorter durations, and direct flights contribute significantly to price variations.
- **Feature Importance**: Features like airline type, source, destination, and total stops have a strong impact on flight prices.
- **Model Performance**: The best-performing model achieved an MAE of X and an R² score of Y (replace with actual values).

These findings could assist both airlines and customers in understanding factors that affect flight pricing.
