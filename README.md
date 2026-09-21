# 🚗 Used Car Price Prediction Model - Cars24 Business Case

This project is built as part of a real-world business case for Cars24, one of India's leading platforms for buying and selling pre-owned cars. The objective is to automate the pricing mechanism using a machine learning model that estimates the price of a used car based on its specifications and condition, replacing manual and rule-based processes.

## Description

Traditionally, used car prices are calculated using:

- Historical price records for similar models
- Rule-based depreciation methods
- Manual condition assessments

These methods are time-consuming, error-prone, and lack personalization. To improve this, a predictive machine learning model was developed to automatically estimate the price of a used car based on relevant attributes such as make, model, age, fuel type, transmission, and more.

This solution empowers pricing analysts, business teams, and non-technical users by delivering fast, consistent, and data-driven price estimates, enhancing decision-making and increasing customer trust.

## Problem Statement

Cars24 currently estimates prices using:

- Past selling prices of the same make and model
- Rule-based depreciation logic
- Manual condition checks

These approaches are:

- Time-consuming
- Inconsistent
- Not scalable

Goal: Build a predictive model to estimate used car prices automatically and accurately.

## Solution

Using supervised learning, a regression model was trained on historical car listings to predict prices based on relevant features such as:

- Make and Model
- Year of Manufacture
- Mileage
- Transmission and Fuel Type
- Owner history
- Engine size, torque, etc.

## Tech Stack

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Regression models)
- Jupyter Notebook / Google Colab
