# User Engagement Analysis For Restaurant Success:
Yelp Dataset Anlaysis For Extracting  Deep Insights To Enable Restaurant Success
"""
# Yelp Dataset Analysis and Database Project

This repository contains two main components:

1. **Analysis**: Investigates factors affecting restaurant success using Yelp's dataset.
2. **Database Creation**: Processes large JSON files from Yelp's dataset and stores them in an SQLite database for efficient data retrieval.

---

## **Analysis Overview**

### **Problem Statement**
In the competitive restaurant industry, understanding factors influencing business success is vital. This analysis focuses on user engagement metrics and their correlation with review counts and ratings.

### **Research Objectives**
- Quantify the relationship between user engagement (reviews, tips, check-ins) and success metrics (review count, average star rating).
- Assess the impact of sentiment on reviews and ratings.
- Analyze time trends in user engagement to identify sustained versus sporadic activity.

### **Hypotheses**
- Higher user engagement correlates with increased review counts and ratings.
- Positive sentiment in reviews and tips leads to higher ratings and review counts.
- Consistent user engagement over time is linked to long-term restaurant success.

### **Tools & Libraries Used**
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Folium
- **Database Interaction**: SQLite, SQLAlchemy

---

## **Database Creation**

### **Dataset Details**
- The dataset contains information on businesses, reviews, users, tips, and check-ins across 8 metropolitan areas in the USA and Canada.
- Original data is shared by Yelp as JSON files.

### **Process**
1. **Large-Scale JSON Processing**:
   - Processed JSON files in chunks for scalability.
   - Files include:
     - `yelp_academic_dataset_business.json`
     - `yelp_academic_dataset_checkin.json`
     - `yelp_academic_dataset_review.json`
     - `yelp_academic_dataset_tip.json`
     - `yelp_academic_dataset_user.json`
2. **Database Loading**:
   - Created tables for each JSON file in SQLite.
   - Used SQLAlchemy for efficient database interaction.

### **Database Schema**
- **Tables**:
  - `business`
  - `review`
  - `user`
  - `tip`
  - `checkin`

---

## **Visualizations and Insights**

### **Graphs and Trends Analyzed**
- Correlation heatmaps to identify relationships between user engagement and success metrics.
- Time-series plots to explore trends in user engagement.
- Sentiment analysis charts to highlight the impact of positive reviews.

### **Sample Visualization**
![Correlation Heatmap](images/correlation_heatmap.png)

---

## **How to Use**

1. Clone this repository:
   ```bash
   git clone https://github.com/SyedTathahir/Yelp-Analysis-Project.git
