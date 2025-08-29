# ClimateWins ML Predictions

This project explores how machine learning can be used to predict “pleasant” weather days based on historical temperature data from across Europe. It was developed for ClimateWins, a nonprofit focused on analyzing climate patterns and their impact on human habitation.

## Project Overview

Using daily weather data from 18 European stations (1960–2022), we tested multiple machine learning algorithms to classify each day as “pleasant” or “unpleasant.” Our goal was to identify the most effective models while also uncovering bias and regional variation in prediction accuracy.

Part 1: Focused on supervised learning to test baseline models and uncover challenges such as bias, class imbalance, and regional differences.

Part 2: Expanded into advanced machine learning techniques, including unsupervised learning, deep learning, and generative models, to identify unusual weather patterns, simulate future conditions, and map safe living regions in Europe for the next 25–50 years.

## Methods Used

- Data source: [European Climate Assessment & Dataset (ECAD)](https://www.ecad.eu/)

**Part 1 – Supervised Models**  
- **Algorithms:**  
  - K-Nearest Neighbors (KNN)  
  - Decision Tree  
  - Artificial Neural Network (ANN)  
- **Optimization:**  
  - Gradient Descent for temperature modeling  
  - Hyperparameter tuning for ANN (layers, nodes, iterations)  
- **Evaluation:**  
  - Confusion matrices  
  - Accuracy scores  
  - Bias analysis (class imbalance, temporal variation, location-specific skew)  

**Part 2 – Advanced Models**  
- **Unsupervised Learning:**  
  - Clustering (K-means, hierarchical, PCA for dimensionality reduction)  
- **Complex Models (Keras/TensorFlow):**  
  - Convolutional Neural Networks (CNNs)  
  - Recurrent Neural Networks (RNNs)  
  - Random Forests
- **Optimization:**  
  - Hyperparameter tuning (Bayesian optimization, grid/random search)  
- **Generative Models:**  
  - Generative Adversarial Networks (GANs) to synthesise realistic weather data  
- **Applications:**  
  - Anomaly detection for unusual weather  
  - Simulation of climate scenarios over 25–50 years  
  - Regional resilience mapping to identify safe living areas  

## Tools Used

- Python (Pandas, NumPy, scikit-learn, Matplotlib, TensorFlow, Keras)
