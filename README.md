---

# Big Data Analytics for Weather Pattern Analysis

## Team Members
 - Sourva Ganesha (40228888)
 - Jay Dhanani (40232469)
 - Navjyot Singh (40231127)
 - Sindoora S Rao (40199155)

## Project Summary

In recent years, the advent of big data technologies and artificial intelligence has revolutionized various domains, including meteorology. Our project, "Big Data Analytics for Weather Pattern Analysis," aims to leverage these advancements to enhance weather forecasting accuracy and provide deeper insights into climate trends.

### Dataset

Our primary data source is a comprehensive weather dataset from Kaggle, encompassing historical hourly weather data from 36 cities between 2012 and 2017. This dataset is rich in features, including visibility, wind speed and direction, precipitation levels, cloud coverage, temperature, perceived temperature, atmospheric pressure, humidity, and sea level pressure. By analyzing these diverse attributes, we can develop a more nuanced understanding of weather patterns.

### Model Design and Architecture

The architecture of our system is designed to efficiently handle and process large volumes of data:

- **Data Source**: The dataset is sourced from Kaggle (https://www.kaggle.com/datasets/selfishgene/historical-hourly-weather-data), known for its reliability and comprehensive coverage of weather parameters.
- **Data Preprocessing**: Initial analysis and exploration are conducted to understand the data's structure and to perform necessary transformations, ensuring compatibility with our analytical models.
- **Data Processing**: The dataset is organized into separate CSV files for each attribute. Our objective is to consolidate these into a unified DataFrame, encompassing all hourly measurements. Furthermore, we aim to simplify the diverse weather conditions into a set of common categories for easier analysis.
- **Storage**: We employ HDFS (Hadoop Distributed File System) for its scalability and reliability in storing extensive datasets.

### Research Questions

Our project seeks to address several key research questions:

1. How can historical weather data be utilized to predict future weather conditions with high accuracy?
2. What are the primary indicators of severe weather patterns, and how can they be detected early to mitigate potential impacts?
3. Can the application of big data analytics significantly improve the precision of local weather forecasts?

### Models and Algorithms

To tackle these questions, we will explore and compare various models and algorithms:

- **Random Forest**: An ensemble learning method known for its effectiveness in handling nonlinear relationships and resistance to overfitting, making it ideal for complex weather data.
- **Logistic Regression**: A statistical model used for predicting binary outcomes, which can be applied to weather classification tasks.

## Evaluation

The success of our project will be measured by the accuracy of our weather forecasts and our ability to predict severe weather events. We will benchmark our predictions against the forecasts provided by OpenWeatherMap, ensuring our models are competitive and reliable.

---
