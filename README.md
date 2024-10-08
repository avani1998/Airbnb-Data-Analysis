# Airbnb Data Analysis
<div align="center">
    <img src="/airbnb.png" alt="drawing" width="600"/>
</div>

## Project Overview
This project analyzes a dataset focusing on Airbnb listings. Key steps include data cleaning, visualization, hypothesis testing, and K-Means clustering of GPS locations.

### Dataset Details:

- **Source**: [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
- **File**: listings.csv.gz
- **Location**: Rio de Janeiro
- **Date Range**: January 2020

### Description:

The dataset contains detailed information about Airbnb listings in Rio de Janeiro, including attributes such as host information, property type, pricing, reviews, and geographical coordinates. By analyzing this dataset, insights into the Airbnb market dynamics and host-guest interactions in Rio de Janeiro can be gained.

## Key Insights

After analyzing the Airbnb dataset, several key insights were uncovered:

1. **Price Distribution**: The histogram of prices revealed that most listings fall within the range of $40 to $830, with a few outliers priced higher.
2. **Location Analysis**: The correlation heatmap and geographical visualization highlighted that certain regions, like Rio de Janeiro, tend to have higher-priced listings.
3. **Outlier Detection**: Utilizing the interquartile range method, outliers in attributes like price and host listing count were identified and addressed, improving the dataset's reliability.
4. **Hypothesis Testing**: Statistical tests revealed significant relationships between various attributes.
   
   i. The result of the t-test comparing the **"price"** and **"beds"** suggests that there is a statistically significant difference between these two attributes. This indicates that there is strong evidence to suggest that there is indeed a relation between the price and the number of beds in the dataset.
   
   ii. The p-value (3.66e-250) of result of the t-test comparing the **"price"** and **"host_total_listings_count"** is far smaller than the typical significance level of 0.05, we reject the null hypothesis. This indicates that there is strong evidence to suggest that there is indeed a relation between the price and the host listing count in the dataset.
   
6. **K-Means Clustering**: Applying K-Means clustering to GPS locations helped identify spatial patterns in listing distribution, facilitating further analysis of regional dynamics. We see from teh elbow curve that the optimal numebr of clusters is 4 indicating that there are 4 areas that define the Rio de Janerio airbnb space.
7. **Accomodatiion Type** : The most popular airbnb room type in Rio de Janeiro are "Entire home/apt" and next most popular are the private rooms where as hotel rooms are 
the least popular.  

These insights provide valuable information for understanding the Airbnb market and can guide decision-making processes for both hosts and guests. 
