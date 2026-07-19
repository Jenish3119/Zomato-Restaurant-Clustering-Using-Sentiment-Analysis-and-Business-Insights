# 🍽️ Zomato Restaurant Clustering using Sentiment Analysis and Business Insights

## 📌 Project Overview

This project analyzes Zomato restaurant reviews and metadata to discover meaningful restaurant segments using **Natural Language Processing (NLP)** and **Unsupervised Machine Learning**.

The project extracts customer sentiment from restaurant reviews, performs extensive exploratory data analysis, engineers restaurant-level features, and applies clustering algorithms to group similar restaurants based on customer behavior, pricing, engagement, and overall performance.

The generated clusters provide valuable business insights that can improve restaurant recommendations, targeted marketing strategies, and customer experience.

---

# 🎯 Problem Statement

Zomato contains thousands of restaurants with diverse cuisines, pricing, ratings, and customer reviews. Identifying restaurants with similar characteristics manually is difficult.

The objective of this project is to analyze customer reviews using NLP, generate sentiment scores, engineer meaningful restaurant-level features, and segment restaurants into meaningful groups using clustering algorithms.

---

# 📂 Dataset

The dataset contains:

- Restaurant Name
- Cuisine
- Cost for Two
- Customer Rating
- Customer Reviews
- Pictures Uploaded
- Review Metadata

---

# ⚙️ Project Workflow

```
Dataset Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Text Preprocessing
        │
        ▼
Sentiment Analysis (VADER)
        │
        ▼
Feature Engineering
        │
        ▼
Restaurant-Level Aggregation
        │
        ▼
Feature Scaling
        │
        ▼
PCA
        │
        ▼
Clustering Algorithms
        │
        ▼
Business Insights
```

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- SciPy
- WordCloud

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Removing duplicate records
- Lower casing
- Contraction expansion
- Removing punctuation
- Removing URLs
- Removing stopwords
- Tokenization
- Lemmatization
- Sentiment Analysis using VADER

---

# 📊 Exploratory Data Analysis

Several visualizations were created to understand the dataset:

- Rating Distribution
- Restaurant Cost Distribution
- Cuisine Distribution
- Review Count Analysis
- Cost vs Rating
- Word Cloud
- Correlation Heatmap
- Cost Category Analysis
- Restaurant Ranking
- Customer Engagement Analysis
- Hypothesis Testing

---

# 🧠 Feature Engineering

Restaurant-level features created include:

- Average Rating
- Rating Standard Deviation
- Review Count
- Average Sentiment Score
- Average Review Length
- Average Word Count
- Average Pictures Uploaded
- Cuisine Count
- Positive Review Percentage
- Negative Review Percentage

---

# 🤖 Machine Learning Models

Three clustering algorithms were implemented:

### 1. K-Means Clustering

- Elbow Method
- Silhouette Score

### 2. Agglomerative Clustering

- Dendrogram
- Silhouette Score

### 3. DBSCAN

- Hyperparameter tuning using eps and min_samples
- Silhouette Score

---

# 📈 Model Performance

| Model | Silhouette Score |
|--------|-----------------:|
| K-Means | 0.331 |
| Agglomerative Clustering | 0.334 |
| DBSCAN | **0.692** |

**Best Model:** DBSCAN

---

# 💡 Business Insights

The clustering analysis identified meaningful restaurant segments based on:

- Pricing
- Customer Satisfaction
- Review Sentiment
- Customer Engagement
- Cuisine Diversity

These insights can help:

- Improve restaurant recommendations
- Design targeted marketing campaigns
- Identify premium restaurants
- Detect underperforming restaurants
- Improve customer retention
- Support pricing strategies

---

# 📷 Project Visualizations

- Rating Distribution
- Restaurant Cost Distribution
- Cuisine Analysis
- Correlation Heatmap
- Word Cloud
- PCA Visualization
- Cluster Visualization
- Dendrogram
- Business Insight Charts
---

# 🚀 Future Improvements

- Deploy using Streamlit
- Real-time restaurant recommendation system
- Deep Learning based sentiment analysis
- Transformer models (BERT/RoBERTa)
- Location-aware restaurant clustering
- Interactive dashboard using Power BI or Tableau

---

# 📌 Conclusion

This project demonstrates how Natural Language Processing, Feature Engineering, and Unsupervised Machine Learning can be combined to analyze restaurant reviews and segment restaurants into meaningful groups.

Among the implemented clustering algorithms, **DBSCAN** achieved the best performance with a **Silhouette Score of 0.692**, providing well-separated restaurant clusters that can support data-driven business decisions and improve customer experience.

---
