# 911 Calls Data Analysis Project 🚨📊

## Overview

This project involves analyzing 911 call data from Kaggle, aiming to uncover patterns and insights through exploratory data analysis and visualization.

## Dataset Description

The dataset includes fields such as latitude, longitude, emergency call description, zipcode, title, timestamp, township, address, and a dummy variable.

## Project Details

### Data and Setup

- **Libraries Used:** `numpy`, `pandas`, `seaborn`, `matplotlib`
- **Reading Data:** Dataset loaded from `911.csv` using `pd.read_csv()`.
- **Data Information:** Overview obtained using `df.info()`.
- **Sample Data:** Initial exploration via `df.head()`.

### Analysis

- **Top 5 Zipcodes:** Identified zipcodes with the highest 911 call volumes.
- **Top 5 Townships:** Highlighted townships with the most emergency calls.
- **Unique Title Codes:** Counted unique emergency call types.

### Feature Engineering

- **Reason Column:** Extracted department/reason from 'title' to enhance clarity.

### Time Analysis

- **Timestamp Conversion:** Converted 'timeStamp' to DateTime for detailed time-based analysis.
- **Hourly, Monthly, Day of Week Analysis:** Explored call trends across different time frames.

### Visualization

- **Countplots:** Visualized distribution of call reasons, day of the week trends, and monthly variations.
- **Heatmaps and Clustermaps:** Mapped patterns across hours and days for deeper insights.

## Conclusion

This project unveiled intriguing insights into 911 call data, revealing that certain zipcodes and townships experience higher emergency call volumes. The analysis also highlighted distinct patterns in call reasons over different time frames, suggesting potential areas for resource allocation and emergency preparedness improvements. By leveraging data visualization techniques, this project offers a compelling narrative on emergency response dynamics, essential for informing strategic decisions and enhancing public safety. 🌟💼

