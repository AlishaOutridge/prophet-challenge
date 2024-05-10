# MercadoLibre Search Trend Forecasting

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Forecasting Model](#forecasting-model)
4. [Results and Discussion](#results-and-discussion)

## Introduction

This project aims to analyze and forecast search trends for MercadoLibre using the Prophet time series forecasting tool. The objective is to understand the dynamics of search patterns over time and predict future trends, aiding in strategic business decisions and marketing.

## Data

The dataset comprises hourly search trends data from MercadoLibre, structured to reflect various metrics of search intensity over several years. The data has been preprocessed to meet the requirements of the Prophet model, including setting the datetime index and handling missing values.

## Forecasting Model

We utilize Facebook's Prophet forecasting model, known for its robustness to missing data and trend shifts. It typically performs well with daily periodicity data. The model settings have been customized to accurately capture seasonality and trends.

## Results and Discussion

### Data Insights

- **Trend Analysis**: The trend component indicated a general increase in Google search activity over the years, suggesting growing interest in MercadoLibre's offerings. There was a notable spike around 2020, possibly due to the COVID-19 pandemic, which boosted online commerce activities.

- **Seasonality Insights**:
  - **Weekly Trends**: Tuesday emerged as the peak day for search activities, indicating heightened user engagement at the start of the week. This insight can be used to schedule marketing campaigns or promotional activities to maximize visibility and engagement.
  - **Yearly Trends**: There was a noticeable drop in search activities at the beginning of each year, particularly in January, likely reflecting a post-holiday slowdown. This period could be optimal for planning and implementing new strategies or maintenance tasks.
  - **Daily Trends**: Searches peaked around 8:30 PM to midnight, indicating that evenings are when most users are active on MercadoLibre. This insight can help in scheduling live events, auctions, or special promotions to capture the maximum audience.

### Forecasting and Predictions

The forecasting model predicted a slight decline in search trends immediately following a recent peak, likely indicating a transient correction after a surge. The predictions also included uncertainty intervals that widened over time, reflecting increasing unpredictability in long-term forecasts.

### Concluding Thoughts

This analysis has provided crucial insights into the search behavior on MercadoLibre, highlighting the importance of temporal dynamics in e-commerce. Moving forward, continually updating the forecasting models with new data and refining the predictions will be key to staying ahead in a competitive landscape.

The detailed component analysis from Prophet also underscores the model's robustness in handling different types of seasonality, making it a valuable tool for similar analyses in other domains or platforms.
