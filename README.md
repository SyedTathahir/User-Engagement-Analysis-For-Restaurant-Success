# User Engagement Analysis For Restaurant Success:
Yelp Dataset Analysis For Extracting Deep Insights To Enable Restaurant Success

## Yelp Dataset Analysis and Database Project

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

---

## **Database Creation**
<div style="text-align: center;">
  <img src="img/restaurant_database.png" alt="Database Schema" style="max-width: 100%; height: auto;">
</div>

### **Dataset Details**
The dataset contains information on businesses, reviews, users, tips, and check-ins across 8 metropolitan areas in the USA and Canada. Original data is shared by Yelp as JSON files.

---

## **Visualizations and Insights**

### Key Metrics
<div style="text-align: center;">
  <img src="img/Analysis_and_findings.png" alt="Key Metrics" style="width: 40%; max-width: 500px; height: auto;">
</div>

- Out of 150,000 businesses, 35,000 are restaurant businesses that are currently open.

<div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
  <img src="img/highestrating.png" alt="Highest Ratings" style="width: 45%; max-width: 250px; height: auto;">
  <img src="img/highesreview.png" alt="Highest Reviews" style="width: 40%; max-width: 200px; height: auto;">
</div>

---

## Correlation Between Reviews, Tips, and Check-ins
<div style="text-align: center;">
  <img src="img/correlation_reveiw_checkin.png" alt="Correlation Analysis" style="max-width: 100%; height: auto;">
</div>

---

## Engagement Differences Between High-Rated and Low-Rated Businesses
<div style="text-align: center;">
  <img src="img/difference.png" alt="Engagement Differences" style="max-width: 100%; height: auto;">
</div>

---

## How do the success metrics of restaurants vary across different states and cities?
<div style="text-align: center;">
  <img src="img/across_states.png" alt="State-wise Analysis" style="max-width: 100%; height: auto;">
</div>

---

## Are there any patterns in user engagement over time for successful businesses compared to less successful ones?
<div style="text-align: center;">
  <img src="img/patternsuserengagement.png" alt="User Engagement Patterns" style="max-width: 100%; height: auto;">
</div>

---

## How does the sentiment of reviews and tips (useful, funny, cool) correlate with the success metrics of restaurants?
<div style="text-align: center;">
  <img src="img/successmetrics.png" alt="Sentiment Metrics" style="max-width: 100%; height: auto;">
</div>

---

## Elite vs. Non-Elite Users
<div style="text-align: center;">
  <img src="img/piechart.png" alt="Elite vs. Non-Elite" style="max-width: 100%; height: auto;">
</div>

---

## Busiest Hours
<div style="text-align: center;">
  <img src="img/busiesthours.png" alt="Busiest Hours" style="max-width: 100%; height: auto;">
</div>
