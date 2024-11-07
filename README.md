# E-Commerce Recommendation System

This project implements an e-commerce recommendation system using Python. The system leverages machine learning techniques such as unsupervised learning, fuzzy matching, and neural networks to generate personalized product recommendations based on various features from a dataset published by Walmart.

## Features

- **Dataset**: The system uses a dataset containing fields like Product Name, Product Price, Product Rating, Product Reviews Count, Product Category, Product Brand, Product Description, and more.
- **Techniques Used**:
  - **Unsupervised Learning**: Clustered products to identify patterns and recommend similar items.
  - **Fuzzy Matching**: Improved product matching and recommendations based on name and description similarity.
  - **Neural Networks**: Applied deep learning models to enhance the recommendation accuracy and personalization.
- **Evaluation Metrics**: The model performance is evaluated using metrics like Match Score and Ranking to ensure high-quality recommendations.

## Tools and Libraries

- **Python**: Core language for implementing the recommendation system.
- **pandas**: For data manipulation and analysis.
- **scikit-learn**: For clustering, machine learning models, and metrics.
- **TensorFlow / Keras**: For building neural network models.
- **fuzzywuzzy**: For fuzzy matching of product names and descriptions.

## Project Structure

1. **Data Preprocessing**: Cleans and prepares the dataset by handling missing values and feature extraction.
2. **Model Training**: Includes training unsupervised models (such as K-Means) and a neural network model for recommendation generation.
3. **Recommendation Generation**: Generates product recommendations based on user interaction or similarity measures.
4. **Evaluation**: The system evaluates recommendation accuracy through Match Score and Rank Evaluation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/e-commerce-recommendation-system.git
