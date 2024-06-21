# 911 Calls Data Analysis Project 🚨📊

## Overview

This project involves analyzing 911 call data from Kaggle, focusing on gaining insights through exploratory data analysis and visualization.

## Dataset Description

The dataset includes fields such as latitude, longitude, emergency call description, zip code, title, timestamp, township, address, and a dummy variable.

## Project Details

### Data and Setup

- **Libraries Used:** `numpy`, `pandas`, `seaborn`, `matplotlib`
- **Reading Data:** Dataset loaded from `911.csv` using `pd.read_csv()`.
- **Data Information:** Overview obtained using `df.info()`.
- **Sample Data:** Initial exploration via `df.head()`.

### Analysis

- **Top 5 Zipcodes:** Identification of the zipcodes with the highest 911 call volumes.
- **Top 5 Townships:** Township analysis highlighting the busiest areas.
- **Unique Title Codes:** Counting unique emergency call titles.

### Feature Engineering

- **Reason Column:** Extraction of department/reason from 'title' for clearer insights.

### Time Analysis

- **Timestamp Conversion:** Conversion of 'timeStamp' to DateTime for time-based insights.
- **Hourly, Monthly, Day of Week Analysis:** Analysis of call trends across different time frames.

### Visualization

- **Countplots:** Visualizing call reasons, day of week, and month.
- **Heatmaps and Clustermaps:** Pattern visualization across hours and days.

## Conclusion

This README provides an enticing overview of the 911 Calls Data Analysis Project, showcasing data exploration, feature engineering, time-based insights, and vivid visualizations. Ideal for recruiters interested in analytical prowess and insightful data storytelling! 🌟💼
