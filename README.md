# Airline Recommender System

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

This is a data mining project that aims to build an Airline Recommender System. The system analyzes customer preferences and provides personalized recommendations for airlines based on their needs and preferences.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Airline Recommender System project utilizes data mining techniques to analyze customer data and provide personalized recommendations for airlines. By understanding customer preferences, the system aims to enhance the overall customer experience and satisfaction in the airline industry.

## Features

- Customer profiling: Analyzes customer data to understand preferences, such as destination, travel class, and flight duration.
- Collaborative filtering: Recommends airlines based on similar customers' preferences and behaviors.
- Content-based filtering: Provides recommendations by matching customer preferences with airlines' features and attributes.
- Hybrid approach: Combines collaborative and content-based filtering techniques to generate accurate and diverse recommendations.
- Evaluation metrics: Measures the performance of the recommender system using metrics like precision, recall, and F1-score.

## Dataset

The project utilizes a dataset from [Airline Data Repository](https://www.kaggle.com/datasets/arjhbholu/airline-dataset-mining). The dataset contains anonymized customer information, including demographic data, travel history, and customer ratings.


## Usage

### Data Cleaning

#### Outliers

Outliers in the dataset were identified and handled using appropriate techniques to ensure data integrity.

#### Merging Similar Columns

Similar columns were merged to improve data efficiency and reduce redundancy, preserving relevant information.

### Data Visualization

#### Correlation between Columns

Visualizations were used to explore the correlations between different columns, providing insights into variable relationships.

#### Multivariate Relations

Visualizations were employed to analyze complex patterns and dependencies among multiple variables.

### Logistic Regression

Logistic Regression, a predictive modeling technique, was utilized to analyze the relationship between the target variable and various features, enabling predictions and conclusions.

### K-Nearest Neighbors

The K-Nearest Neighbors algorithm was used for classifying and recommending airlines based on similarity to other customers, providing personalized recommendations.

### Association Rules Mining (Apriori Algorithm)

The Apriori algorithm was employed to identify frequent item sets and generate association rules, revealing patterns and associations among different attributes.

### Sentiment Analysis with Random Forest Classifier

Sentiment analysis was performed using a Random Forest Classifier to assess customer satisfaction based on their reviews and sentiments.


## Results

We have created a highly trained Airline Recommendation model to predict
whether any customer would recommend a particular airline based on various
different airline attributes.
This would be helpful for other customers while booking an airline of their choice
based on other customer ratings, as well as help airlines improve based on
customer feedback.
Based on the observations from the above-mentioned models, we concluded that:
● The best airlines most people recommend and have a good overall rating
are Aeroflot-Russian-airlines, BMI-British-midland-international,
garuda-Indonesia, Korean-air, and royal-Brunei-airlines.
● The airlines having least ratings are air-Canada-rouge, American-airline,
frontier-airline, royal-air-Maroc, spirit-airline, Sunwing, and united-airline.
● We saw that inflight entertainment had contributed very less to overall
ratings and recommendations, so airlines should focus more on other
features like seat comfort, cabin staff, and food beverages.
● Passengers with an overall rating of 4 and below did not recommend the airline.
● Based on the sentiment analysis, we can conclude that most people were happy
with their airlines and would recommend them.
● If the customer has traveled in the economy and business class, there is a high
chance the customer would recommend the airline. Instead, if customers have
traveled in first class and premium economy, they won’t recommend it.

## Contributing

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please submit a pull request. For major changes, please open an issue to discuss the proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

---
