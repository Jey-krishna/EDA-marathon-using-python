# EDA marathon running using python
This repository contains an exploratory data analysis (EDA) of a comprehensive dataset on ultra-marathon running events. The dataset spans over two centuries and provides detailed information on various ultra-marathon races, athletes, and their performances.

## Dataset
The dataset used in this analysis is sourced from Kaggle: [The Big Dataset of Ultra-Marathon Running](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running). It includes information on race events, distances, athlete demographics, and performance metrics.

## Analysis Overview
The Jupyter notebook `EDA_marathon_running.ipynb` covers the following steps:

1. **Data Acquisition**
    - Downloading the dataset using the Kaggle API.
    - Extracting the data from the downloaded zip file.

2. **Data Preprocessing**
    - Loading the dataset into a pandas DataFrame.
    - Initial exploration of the dataset (shape, data types, missing values).
    - Filtering the dataset for specific criteria (e.g., events in 2020, races held in the USA).
    - Cleaning and transforming data columns for analysis.

3. **Exploratory Data Analysis (EDA)**
    - Visualizing the distribution of race distances and athlete genders.
    - Analyzing the relationship between athlete age and performance.
    - Comparing average speeds across different event distances and genders.

## Visualizations
Several visualizations are generated to understand the data better:
- Count plots for event distances and athlete genders.
- Violin plots for athlete speeds across event distances.
- Line plots showing the relationship between athlete age and average speed.

## Dependencies
To run the notebook, you need the following Python libraries:
- pandas
- seaborn
- matplotlib
- kaggle

## Conclusion
This analysis provides insights into ultra-marathon running events, highlighting trends and patterns in athlete performances based on gender, age, and event distances. Further analysis can be conducted to explore additional aspects of the dataset.


