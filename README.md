# Airbnb-Bookings-Analysis

## Table Of Contents
- [Introduction](#Introduction)
- [Overview](#Overview)
- [About the Dataset](#About-the-Dataset)
- [Objectives](#Objectives)
- [Workflow of the project](#Work-flow-of-the-project)
- [Conclusion](#Conclusion)

## Introduction
Airbnb is a platform that connects homeowners with individuals seeking affordable accommodations worldwide. In addition to lodging, the service offers unique experiences—curated activities led by locals—such as sunset surfing, hiking with rescue dogs, and guided food tours.

New York City, renowned for its influence on global finance, politics, culture, and entertainment, is one of the most iconic destinations in the world. With landmarks like Central Park, renowned museums, towering skyscrapers, and vibrant shopping districts, it draws millions of tourists year-round. As with other major cities, visitors to NYC can choose from a wide range of lodging options, including Airbnb.

## Overview
This project focuses on analyzing the Airbnb dataset for New York City from 2019 to uncover trends, patterns, and insights. The analysis includes exploratory data analysis (EDA), data visualization, and business recommendations to provide valuable information for travelers, hosts, and property managers.

## About the Dataset
**[AIRBNB BOOKINGS](https://drive.google.com/file/d/1RQ1Cqk0BdknEbA55CUaNNXTwuM_iZUn2/view?usp=sharing)**

- The dataset consists of 48,895 Airbnb listings in New York City from 2019. It contains 16 columns, with details about each listing.
- The Data includes both categorical and numeric values wherein name, host_name, neighbourhood_group, neighbourhood, room_type are categorical columns and id, host_id, latitude, longitude, price, minimum_nights, number_of_reviews, reviews_per_month,calculated_host_listings_count, availability_365 are numerical columns.
- There are five different neighborhood groups, 221 neighborhoods, 37,457 hosts, 48,895 listings, and three types of room available for rental.

## Objectives
- Analyze trends in pricing, availability, and demand across NYC boroughs.
- Identify outliers and clean the dataset for better analysis.
- Discover patterns in room types, minimum nights, and reviews.
- Provide actionable recommendations for hosts and travelers.

## Technologies Used
- Programming Language: Python
- Libraries:
  - Pandas, NumPy: Data manipulation
  - Matplotlib, Seaborn: Visualization
- IDE: Google Colab
- Version Control: Git

## Work flow of the project
- Importing Libraries
- Loading the Dataset
- Exploring the Dataset
- Data Cleaning
- Handling Outliers
- Data Visualization
- Solution to Business Objective
- Conclusion

## Conclusion
The analysis of Airbnb NYC listings highlights Manhattan as the most expensive and competitive borough, driven by high demand and occupancy for entire homes, while Brooklyn balances affordability and proximity to attractions. Popular neighborhoods like Williamsburg and Hell's Kitchen dominate listings, contrasting with lower demand in Staten Island and the Bronx. Room types influence pricing, with entire homes commanding higher rates, and frequent reviews boosting listing popularity. These insights guide hosts in pricing strategies, targeting guest preferences, and optimizing occupancy in NYC's dynamic market.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/RahulChakravorty/airbnb-2019-analysis.git
2.Install required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3.Run the Jupyter Notebook to explore the data and visualizations:
   ```bash
   jupyter notebook Airbnb_EDA.ipynb

