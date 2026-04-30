# behavior-analysis-project

## Clustering Analysis of University Student Life and Study Patterns

## 📌 Project Overview

This project focuses on analyzing university students' study habits and life patterns using machine learning clustering techniques. The main objective is to understand the effectiveness of listening to lectures vs. self-study and identify meaningful student groups based on their behaviors.

The project was developed as part of the Machine Learning and Big Data Analytics (ITE 3153) course.

## 🎯 Objectives
Collect and preprocess student data related to study habits
Analyze effectiveness of self-study vs lecture-based learning
Apply clustering algorithms to identify student patterns
Provide insights and recommendations for better learning strategies

## 🗂️ Dataset
Data collected using Google Forms
100+ responses from university students
Includes:
Demographic details
Study hours (self-study vs lectures)
Retention levels
Preferred learning methods
Challenges faced

## ⚙️ Technologies Used
Python
Google Colab
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn

## 🔄 Data Preprocessing
Data Cleaning (handled missing values & duplicates)
Outlier Detection using Z-score method
Encoding:
Label Encoding
One-Hot Encoding
Feature Scaling using StandardScaler

## 🤖 Clustering Techniques Used
K-Means Clustering
Hierarchical Clustering
DBSCAN
Gaussian Mixture Model (GMM)
Spectral Clustering

## 📊 Evaluation Method
Silhouette Score used to evaluate clustering performance
1 → Well clustered
0 → Overlapping clusters
Negative → Poor clustering

## 📈 Results Summary
Algorithm	Clusters	Silhouette Score
K-Means	2	0.2455
Hierarchical	2	0.2481
DBSCAN	2	0.38 (Best)
GMM	2	0.238
Spectral Clustering	3	0.220

## 👉 Best Model: DBSCAN

Handles noise effectively
Works well with irregular data patterns

## 🔍 Key Insights
Self-study leads to higher retention compared to lectures
Lecture effectiveness varies among students
Combination of lectures + self-study gives best results
Students can be grouped into different learning behavior clusters

## 📊 Visualizations
Bar Charts
Histograms
Heatmaps
Boxplots
PCA-based cluster visualization

## 💡 Recommendations
Encourage self-study practices among students
Combine lectures with interactive/self-learning methods
Collect more diverse data for better analysis
Use advanced feature engineering for improved clustering

## 🚀 How to Run the Project
Open the project in Google Colab
Upload the dataset (CSV file)
Run all cells step-by-step:
Data preprocessing
Visualization
Clustering models
Compare results using silhouette scores

## 👩‍💻 Author
Prathibha Dissanayake 

## 📚 Conclusion

This project demonstrates how clustering techniques can uncover hidden patterns in student learning behaviors. The findings highlight the importance of self-study and provide valuable insights for improving academic performance.
