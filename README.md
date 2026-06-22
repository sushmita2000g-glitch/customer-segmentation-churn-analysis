📊 Customer Segmentation & Churn Analysis
🚀 Project Overview

This project focuses on analyzing customer behavior and identifying customer segments using Machine Learning. The objective is to understand different customer groups and discover which segments are more likely to churn.

By applying K-Means Clustering, customers were divided into distinct groups based on their service usage and spending patterns. Churn analysis was then performed to identify high-risk customer segments.

🎯 Objectives
Perform customer segmentation using K-Means Clustering
Identify customer groups with similar characteristics
Analyze customer churn patterns
Discover high-risk customer segments
Generate business insights for customer retention

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Google Colab

📂 Dataset
The dataset contains telecom customer information including:

Customer demographics
Service subscriptions
Monthly Charges
Total Charges
Contract details
Payment methods
Customer Churn status

Dataset Size:
7043 Rows
31 Features

🔍 Data Preprocessing
The following preprocessing steps were performed:

1. Data Cleaning
Removed unnecessary columns
Handled missing values
Converted TotalCharges to numeric format
2. Label Encoding

Converted binary categorical variables into numerical values:

Yes → 1
No → 0
3. One-Hot Encoding

Applied one-hot encoding on multi-category columns:

InternetService
Contract
PaymentMethod
MultipleLines
OnlineSecurity
OnlineBackup
DeviceProtection
TechSupport
StreamingTV
StreamingMovies

4. Feature Scaling
Applied StandardScaler before clustering.

📈 Exploratory Data Analysis
Customer Churn Distribution

The churn distribution revealed that a significant number of customers remained active while a smaller portion churned.

Correlation Heatmap

A correlation heatmap was generated to understand relationships between features and customer churn.

🤖 Customer Segmentation
K-Means Clustering

The Elbow Method was used to determine the optimal number of clusters.

Elbow Method

The elbow point indicated:

Optimal Clusters = 3

📊 Customer Segments Visualization
Customer Segments Scatter Plot

This scatter plot shows how customers are grouped into three distinct clusters based on their Monthly Charges and Total Charges.<img width="859" height="547" alt="scatterplot" src="https://github.com/user-attachments/assets/da0134ac-6b15-4331-895e-f2a095b0cf5c" />
<img width="859" height="547" alt="scatterplot" src="https://github.com/user-attachments/assets/dfe43ee9-5681-4c26-8e69-dafc9ff59f8a" />

📋 Cluster Summary
Cluster	Average Tenure	Average Monthly Charges	Average Total Charges
0	29.49	26.57	808.95
1	58.56	89.70	5245.65
2	13.25	74.95	1030.10
🔥 Churn Analysis by Cluster
Cluster	Churn Rate (%)
0	12.30%
1	15.36%
2	47.08%
Key Finding

Cluster 2 has the highest churn rate (47.08%), making it the most vulnerable customer segment.

💡 Business Insights
Cluster 0
Low monthly charges
Moderate tenure
Low churn risk
Cluster 1
High-value customers
Long tenure
Strong customer loyalty
Cluster 2
High churn probability
Short tenure customers
Requires immediate retention strategies
🎯 Recommendations
Offer personalized retention campaigns for Cluster 2.
Provide loyalty rewards to high-value customers in Cluster 1.
Improve onboarding experience for new customers.
Monitor churn-prone customers proactively.
📌 Conclusion

This project successfully segmented telecom customers into meaningful groups and identified the segment most likely to churn. These insights can help businesses improve customer retention strategies and maximize long-term customer value.

👨‍💻 Author

Sushmita Poddar

Aspiring Data Scientist | Machine Learning Enthusiast | Python Developer
