
# 🚗 Predictive Modeling of US Road Accidents

## Overview
This project focuses on analyzing US road accident data to explore how meteorological conditions and geographical factors impact accident severity and clearance times. By leveraging data science techniques, our goal is to identify patterns and trends that can enhance accident prediction, management, and response strategies, ultimately improving road safety.

## Key Research Questions

1. **Severity Prediction**: Can we predict the severity of a car accident based on weather conditions, road features (e.g., junctions, traffic signals), and location details (latitude, longitude)?
2. **Accident Hotspot Detection**: Can clustering techniques identify geographical accident hotspots across different states or counties?
3. **Weather Impact Analysis**: How do weather factors (temperature, humidity, wind speed, precipitation) affect the frequency and severity of accidents?
4. **Time of Day and Accident Severity**: Can accident severity be predicted based on the time of day using attributes like Start_Time, Sunrise_Sunset, and Twilight phases?
5. **Traffic Signals and Accident Likelihood**: How significantly do traffic signals and road features contribute to accident likelihood and severity?
6. **Time-Series Forecasting of Accidents**: Can we develop a time-series model to predict the number of accidents in different regions based on historical trends?
7. **NLP-Based Classification for Automatic Reporting**: Can natural language processing (NLP) classify and summarize accident descriptions for automatic report generation?
8. **Urban vs. Rural Accident Differences**: Can we distinguish accident characteristics between urban and rural areas using city, county, and street data?
9. **Predicting Traffic Delays**: Can a machine learning model forecast traffic delays after accidents based on historical data, traffic conditions, and weather?
10. **Optimizing Emergency Response Deployment**: Can predictive modeling optimize emergency response deployment by forecasting high-risk accident times and locations?

## Dataset
The project utilizes the **US-Accidents dataset**, which records road accidents from February 2016 to March 2023, covering **49 states**. Given the dataset's large size (approximately **7.7 million records**), a **sampled version containing 500,000 records** was used while maintaining representativeness.

The dataset was compiled from multiple real-time traffic incident APIs, sourcing data from:
- **State and US Departments of Transportation**
- **Law enforcement agencies**
- **Traffic cameras**
- **Road network sensors**

This dataset enables applications such as real-time accident prediction, hotspot identification, casualty analysis, and the study of environmental impacts on accidents. Additionally, its temporal span allows for analyzing traffic pattern shifts due to major events like the COVID-19 pandemic.

## Enhancing Weather Data with API Extraction
During data analysis, significant gaps and inaccuracies were found in weather-related fields. To improve data reliability, weather observations at accident times were retrieved using **NASA POWER API** ([NASA POWER](https://power.larc.nasa.gov/)).

- **API Benefits**: Provides location-based historical weather data, allowing precise extraction based on accident latitude, longitude, and date.
- **Meteorological Parameters Collected**: Temperature, precipitation, wind speed, solar radiation, etc.
- **Impact**: Significantly enhanced the completeness and accuracy of weather data, ensuring robust analysis of weather conditions' effects on accidents.

## Features
- **Exploratory Data Analysis (EDA)**: Identifies key trends and correlations in accident data.
- **Association Rule Mining (ARM)**: Extracts hidden relationships between accident conditions.
- **Machine Learning Models**:
  - **Support Vector Machine (SVM)**: Classifies accident severity based on multiple factors.
  - **Gradient Boosting**: Provided the highest accuracy in severity prediction.
  - **Multinomial Naïve Bayes**: Excelled in text-based severity classification.
- **Time-Series Forecasting**: Predicts accident trends using historical patterns.
- **Ensemble Learning**: Combines multiple models to improve predictive performance.

## Tech Stack
- **Data Processing**: Pandas, NumPy, Scikit-learn
- **Machine Learning**: SVM, Gradient Boosting, Naïve Bayes, Decision Trees, Regression
- **Visualization**: Matplotlib, Seaborn


## Conclusion
This project provides data-driven insights into road accidents, helping policymakers and traffic authorities improve accident prediction, emergency response, and road safety initiatives.

For more details, visit the project website: [Project Website](https://suraj23112001.wixsite.com/my-site)

---

