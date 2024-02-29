# DengAI: Predicting Disease Spread

## Introduction
The project documents the collective efforts of our group in tackling the Dengue Fever Prediction challenge organized by DrivenData. Our team worked together to develop predictive models aimed at forecasting the spread of dengue fever, utilizing data provided by DrivenData. For more information about the challenge, you can visit [DrivenData's Dengue Fever Prediction challenge page](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/page/80/).

## Team Members
- [@DevWhiz67](https://github.com/DevWhiz67)
- [@IAKattan](https://github.com/IAKattan)
- [@Kaiko](https://github.com/Kaiko304)

## Objective
The main goal of this project was to develop accurate predictive models to forecast the spread of Dengue fever, contributing to efforts in disease prevention and control.

## Dataset
The dataset supplied by DrivenData contained various climate variables alongside the target variable denoting Dengue fever cases. Prior to model training, we undertook preprocessing tasks including addressing missing values and scaling features.

## Approach
Our approach involved the utilization of diverse machine learning algorithms, namely Negativ Binomial regression, Prophet, SARIMAX and LSTM, to construct predictive models. The assessment of these models was conducted employing metrics such as mean absolute error.

## Results
Our LSTM model, which emerged as the best performer, achieved a mean absolute error of 24.50 on the test dataset. While all models demonstrated the capability to predict seasonality, it was only the LSTM model that successfully identified outbreaks, effectively forecasting all instances of increased Dengue fever cases.








