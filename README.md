# 911_Calls_Data_Analysis_Project

## Overview

This capstone project delves into a dataset containing detailed information about emergency 911 calls. The dataset encompasses a variety of attributes including geographical coordinates, call description, timestamp, zip code, title, township, address, and a dummy variable 'e'. The primary objective of this analysis is to extract meaningful insights from this data, uncovering patterns, trends, and correlations.

---
## Dataset Description

The dataset provides a comprehensive view of emergency calls:

- `lat`: Latitude
- `lng`: Longitude
- `desc`: Description of the Emergency Call
- `zip`: Zipcode
- `title`: Title
- `timeStamp`: Timestamp (in YYYY-MM-DD HH:MM:SS format)
- `twp`: Township
- `addr`: Address
- `e`: Dummy variable (always 1)

---
## Exploratory Data Analysis

### Key Questions Explored

1. **Top 5 Zipcodes for 911 Calls:** Understanding the regions with the highest frequency of emergency calls.
2. **Top 5 Townships for 911 Calls:** Identifying townships that experience the highest number of emergencies.
3. **Unique Title Codes:** Investigating the variety of emergency scenarios represented in the dataset.
4. **Reasons for 911 Calls:** Categorizing calls into 'EMS', 'Fire', and 'Traffic' based on the title.
5. **Temporal Patterns:** Analyzing trends by hour, month, and day of the week.

---

## Detailed Analysis

### Temporal Patterns

- **Hourly Analysis:** Investigated the distribution of calls across different hours of the day. This revealed peak call times, which can be crucial for resource allocation.
- **Monthly Analysis:** Explored the monthly variation in call volumes. This information is valuable for long-term resource planning and identifying seasonal trends.
- **Day of the Week Analysis:** Examined call frequencies for each day of the week, providing insights into weekly patterns.

### Spatial Analysis

- **Heatmaps:** Visualized the spatial distribution of calls, highlighting areas with high call volumes. This information aids in optimizing emergency response strategies.
- **Cluster Maps:** Identified clusters of emergency calls, which can indicate areas with higher incident densities.

---
## Technical Details

The analysis was conducted using Python, leveraging the following libraries:

- Pandas: Data manipulation and analysis
- NumPy: Numerical operations
- Matplotlib: Data visualization
- Seaborn: Advanced data visualization

---
## Usage

To run the analysis, ensure you have the required libraries installed. Execute the Jupyter notebook `911_calls.ipynb` in your Python environment. The notebook contains detailed code for each step of the analysis.

---
## Conclusion

This project provides valuable insights into emergency call patterns. The findings can be instrumental in optimizing emergency response strategies, resource allocation, and long-term planning.

---
## Acknowledgements

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/mchirico/montcoalert).

