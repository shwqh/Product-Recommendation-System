# Product Recommendation System Using Online Retail Data

## Project Overview

This project presents a Product Recommendation System developed using the Online Retail II dataset. The main objective is to analyze customer purchasing behavior and generate product recommendations using different recommendation techniques.

The project applies data preprocessing, exploratory data analysis (EDA), recommendation modeling, and model comparison to evaluate different recommendation approaches and identify their strengths and limitations.

---

## Dataset

The project uses the Online Retail II dataset, which contains transactional records from an online retail store.

### Dataset Source

https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

### Dataset Information

- Original Records: 1,067,371
- Cleaned Records: 805,549
- Attributes: 8

The dataset contains information about customer purchases, product descriptions, quantities, prices, invoice dates, and countries.

---

## Project Objectives

- Analyze customer purchasing behavior.
- Identify popular products.
- Discover product associations using Market Basket Analysis.
- Generate personalized recommendations using Collaborative Filtering.
- Compare different recommendation approaches.
- Support marketing decision-making using data-driven insights.

---

## Recommendation Approaches

### 1. Popularity-Based Recommendation

Recommends the most frequently purchased products based on overall sales volume.

### 2. Association Rules (Apriori)

Uses Market Basket Analysis to discover relationships between products that are frequently purchased together.

### 3. Collaborative Filtering

Uses customer similarity based on purchase history to generate personalized product recommendations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Mlxtend
- Jupyter Notebook

---

## Project Structure

- Data Loading
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Popularity-Based Recommendation
- Association Rules Analysis (Apriori)
- Collaborative Filtering
- Model Comparison
- Conclusion

---

## How to Run the Project

1. Download the dataset from Kaggle:

   https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

2. Place the dataset file in the same directory as the notebook.

3. Open the notebook:

   Project_Ashwag.ipynb

4. Run all notebook cells sequentially.

5. The notebook will perform:

   - Data preprocessing
   - Exploratory Data Analysis (EDA)
   - Popularity-Based Recommendation
   - Association Rules (Apriori)
   - Collaborative Filtering
   - Model Comparison

---

## Key Findings

- The dataset was cleaned from 1,067,371 records to 805,549 valid transactions.
- Popularity-Based Recommendation identified the most purchased products.
- Association Rules discovered frequently purchased product combinations.
- Collaborative Filtering generated personalized recommendations based on customer similarity.
- Collaborative Filtering provided the highest level of personalization among the implemented approaches.

---

## Academic Project

Course: Data Mining

Domain: Marketing

Project Type: Product Recommendation System

---

## Repository Contents

This repository contains:

- Jupyter Notebook implementation
- Data preprocessing workflow
- Exploratory Data Analysis (EDA)
- Recommendation models
- Model comparison
- Project report
- Presentation slides
