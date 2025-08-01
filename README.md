# ClimateWins ML Predictions

This project explores how machine learning can be used to predict “pleasant” weather days based on historical temperature data from across Europe. It was developed for ClimateWins, a nonprofit focused on analyzing climate patterns and their impact on human habitation.

## Project Overview

Using daily weather data from 18 European stations (1960–2022), we tested multiple machine learning algorithms to classify each day as “pleasant” or “unpleasant.” Our goal was to identify the most effective models while also uncovering bias and regional variation in prediction accuracy.

## Hypotheses

- The number of pleasant days has decreased in some regions due to climate change.
- Prediction accuracy will vary based on geographic location and regional climate conditions.
- No single machine learning algorithm will consistently outperform the others across all stations.

## Methods Used

- Data source: [European Climate Assessment & Dataset (ECAD)](https://www.ecad.eu/)
- Algorithms:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Artificial Neural Network (ANN)
- Optimization:
  - Gradient Descent for temperature modeling
  - Hyperparameter tuning for ANN (layers, nodes, iterations)
- Evaluation:
  - Confusion matrices
  - Accuracy scores
  - Analysis of bias: class imbalance, temporal variation, and location-specific skew

## Tools Used

- Python (Pandas, NumPy, scikit-learn, Matplotlib)
