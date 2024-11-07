# Flight Price Prediction Model

This repository contains a project focused on analyzing flight price data to understand patterns and factors that influence flight costs. The project covers data exploration, visualization, and feature analysis, providing insights into factors affecting flight prices.

## Project Overview

The goal of this project is to explore a dataset related to flight prices, analyze relationships between various features (such as time of day, airline, and duration), and understand how these factors contribute to price variation. The project also provides a foundation for developing a flight price prediction model.

### Key Steps in the Process
1. **Data Cleaning**: Handling missing values and preparing data for analysis.
2. **Data Exploration**: Analyzing key statistics and distributions of features.
3. **Feature Analysis**: Investigating relationships between flight price and influential factors.
4. **Visualization**: Using plots and graphs to highlight trends and relationships within the dataset.

## Dataset

The dataset includes several features relevant to flight prices, such as airline, date of journey, departure and arrival times, duration, and price.

### Features in the Dataset

- **Airline**: The airline providing the flight service.
- **Date_of_Journey**: The date of the flight.
- **Departure Time**: Scheduled departure time.
- **Arrival Time**: Scheduled arrival time.
- **Duration**: Total flight duration.
- **Total Stops**: Number of stops between source and destination.
- **Price**: Price of the flight ticket.

## Project Files

- **Flight-Prediction.ipynb**: The main notebook containing the full analysis, from data loading to visualization.
- **Data_Train.xlsx**: The primary dataset used for training the model.
- **Data_Test.xlsx**: A secondary dataset used for testing or additional analysis.

## Installation

To run this project locally, you will need:

- Python (version 3.x)
- Jupyter Notebook
- Required libraries (install using `pip install -r requirements.txt` if a requirements file is provided)

### Required Libraries

- pandas
- numpy
- matplotlib
- seaborn

## Process and Analysis Steps

1. **Data Overview**:
   - A preliminary overview of the dataset was conducted to understand the structure, including the number of entries and range of feature values.

   ![Dataset Overview](images/dataset_overview.png)

2. **Number of Flights vs. Time of Day**:
   - Analyzed the distribution of flight frequency across different times of the day, providing insights into peak and off-peak flight schedules.
   
   ![Number of Flights vs. Time of Day](images/flights_vs_time.png)

3. **Box Plot (Price vs. Airline)**:
   - A box plot was created to analyze the distribution of prices for different airlines, highlighting price variations and identifying premium carriers.

   ![Price vs Airline](images/price_vs_airline.png)

4. **Density Graphs for Outlier Removal**:
   - Density graphs were used to detect and visualize potential outliers in the dataset. These visualizations helped identify extreme values in features such as price and duration, which could be considered for removal to improve model performance.
   
   ![Density Graphs for Outlier Removal](images/density_outlier_removal.png)

5. **Distribution of Price vs. Stops**:
   - A distribution plot was created to analyze the relationship between flight price and the number of stops. This plot revealed insights into how additional stops affect ticket prices, with direct flights generally priced higher than multi-stop flights.
   
   ![Distribution of Price vs Stops](images/price_vs_stops.png)

## Results

After completing the data analysis process, several insights were gained:

- **Dataset Overview**: The data structure was thoroughly examined to identify missing values, potential outliers, and statistical summaries.
- **Flight Frequency by Time of Day**: The analysis showed distinct patterns in flight frequency, with certain times of day experiencing higher flight volumes.
- **Price Variability Across Airlines**: The box plot indicated significant variation in prices among different airlines, reflecting the pricing strategies and service levels of various carriers.
- **Outlier Detection**: Density graphs assisted in identifying outliers within critical features, which may impact the accuracy of predictive models.
- **Impact of Stops on Price**: The distribution plot of price vs. stops highlighted that flights with fewer stops are typically priced higher, aligning with passenger preferences for convenience.

These insights lay the groundwork for developing a predictive model that accurately captures pricing patterns based on key features such as airline, time of day, duration, and number of stops.


