# Hotel Customer Segmentation  

## Introduction  
This project focuses on improving customer segmentation for Hotel H using data science techniques. The goal is to enhance guest experience, optimize marketing strategies, and increase revenue. The hotel previously relied on a basic segmentation model based on customer origin, which failed to capture customer behaviors, booking trends, and spending patterns.  

By applying a data-driven clustering approach, we analyzed customer booking behavior, lead time, revenue contributions, and distribution channels. Through K-Means clustering, four distinct customer groups were identified, enabling personalized marketing, targeted promotions, and optimized pricing models.  

## Table of Contents  
- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Methodology](#methodology)  
- [Technologies Used](#technologies-used)  
- [Results](#results)  
- [Deployment and Maintenance](#deployment-and-maintenance)  
- [Future Improvements](#future-improvements)  
 

## Project Overview  
Hotel H, located in Lisbon, aims to move beyond traditional customer segmentation methods by using clustering techniques to analyze key characteristics such as demographics, booking behaviors, and spending habits. This approach enables better marketing strategies and improved resource allocation.  

## Dataset  
- **Source**: Provided by the Business Cases professor Nuno António at Nova IMS   
- **Size**: 111,733 records, 26 features  
- **Features**: Customer demographics, booking details, revenue, distribution channels, and special requests  
- **Preprocessing**: Handling missing values, removing outliers, and feature engineering  

## Methodology  
1. **Exploratory Data Analysis (EDA)**: Identified key variables and removed inconsistencies.  
2. **Data Preparation**: Cleaned missing values and engineered new features such as total service requests, cancellation rates, and revenue per night.  
3. **Clustering Model**: Applied K-Means clustering to segment customers into four distinct groups.  
4. **Evaluation**: Used the Elbow Method and Silhouette Score to determine optimal cluster count and R² to evaluate the explained variance of the model.  

## Technologies Used  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

## Results
The model identified four key customer segments:

Established, Budget-Conscious Customers: Long-time customers with short stays and minimal spending.
High-Spending, Advanced Planners: Customers with high revenue contributions and early bookings.
Standard, Consistent Customers: Regular guests with predictable booking patterns.
Older, High-Commitment Customers: Loyal guests with long-term booking habits.

## Deployment and Maintenance
A multidisciplinary team is required to maintain the model, including data scientists, engineers, and marketing specialists. Continuous monitoring ensures segment relevance and adaptation to market trends.

## Future Improvements
Exploring alternative clustering algorithms such as Hierarchical Clustering and Gaussian Mixture Models.
Enhancing demographic and behavioral features for deeper insights.
Incorporating seasonal trends to refine booking pattern analysis.

