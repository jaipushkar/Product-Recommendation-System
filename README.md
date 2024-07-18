# Product-Recommendation-System

**All Thanks to **@_611noorsaeed_** for this learning** 

**Overview**
This repository contains a comprehensive recommendation system built using a Walmart product review dataset. The project covers data loading, preprocessing, exploratory data analysis (EDA), data cleaning, tag creation, and implementation of various recommendation techniques, including rating-based, content-based, collaborative filtering, and hybrid recommendations.

**Key Features**
**Data Loading and Preprocessing:** Load the dataset, handle missing values, and rename columns for better readability.
**EDA:** Conduct statistical analysis and create visualizations such as heatmaps and bar charts to understand user behavior and product ratings.
**Data Cleaning and Tag Creation:** Clean the data, fill missing values, and generate tags from product descriptions, categories, and brands.
**Recommendation Systems**
**Rating-Based Recommendation**
**Overview:** Recommends top-rated products based on the average ratings.
**Approach:** Calculate the average rating for each product and recommend the products with the highest average ratings.
**Content-Based Recommendation**
**Overview:** Recommends products similar to a given item based on textual information.
**Approach:**
Use TF-IDF vectorization to convert product tags into numerical vectors.
Calculate cosine similarity between the vectors to find similar products.
Recommend products that are most similar to the given item.
**Collaborative Filtering**
**Overview:** Recommends products based on user-item interactions.
**Approach:**
Create a user-item matrix where rows represent users and columns represent products, with ratings as values.
Calculate cosine similarity between users to find similar users.
Recommend products that similar users have rated highly but the target user has not yet rated.
**Hybrid Recommendation**
**Overview:** Combines content-based and collaborative filtering methods for more robust recommendations.
**Approach:**
Generate content-based recommendations for a given item.
Generate collaborative filtering recommendations for a target user.
Merge and deduplicate the recommendations to provide a comprehensive list.

**Requirements**
Python 3.x
pandas
numpy
matplotlib
seaborn
scikit-learn
spacy
