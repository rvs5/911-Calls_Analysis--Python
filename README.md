# 911 Calls Data Analysis Project

## Overview

This project involves analyzing 911 call data from Kaggle. The dataset includes various fields such as latitude, longitude, description of the emergency call, zipcode, title, timestamp, township, address, and a dummy variable. The goal of this project is to gain insights from the data through exploratory data analysis and visualization.

## Dataset Description

The dataset contains the following fields:

- **lat**: Latitude
- **lng**: Longitude
- **desc**: Description of the Emergency Call
- **zip**: Zipcode
- **title**: Title of the emergency
- **timeStamp**: Timestamp in the format YYYY-MM-DD HH:MM:SS
- **twp**: Township
- **addr**: Address
- **e**: Dummy variable (always 1)

## Project Details

### Data and Setup

- **Libraries Used:** `numpy`, `pandas`, `seaborn`, `matplotlib`
- **Reading Data:** The dataset is read from a CSV file (`911.csv`) using `pd.read_csv()`.
- **Data Information:** Basic information about the dataset is obtained using `df.info()`.
- **Sample Data:** First few rows of the dataset are displayed using `df.head()`.

### Analysis

- **Top 5 Zipcodes:** The top 5 zipcodes with the highest number of 911 calls are identified.
- **Top 5 Townships:** The top 5 townships with the highest number of 911 calls are identified.
- **Unique Title Codes:** Number of unique title codes in the dataset is computed.

### Feature Engineering

- **Reason Column:** A new column 'Reason' is created by extracting the department/reason from the 'title' column.

### Time Analysis

- **Timestamp Conversion:** The 'timeStamp' column is converted to DateTime objects for time-based analysis.
- **Hourly, Monthly, Day of Week Analysis:** Analysis is performed to understand trends and patterns based on hour of the day, month, and day of the week.

### Visualization

- **Countplots:** Visual representation of counts based on reasons for 911 calls, day of the week, and month.
- **Heatmaps and Clustermaps:** Heatmaps are used to visualize data patterns across hours and days of the week.

## Conclusion

This README provides an overview of the 911 Calls Data Analysis Project, detailing the dataset, project setup, analysis steps, and visualizations used to derive insights from the data. For detailed implementation, refer to the respective Python code and visualizations.

