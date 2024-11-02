# Black Friday Dataset - Exploratory Data Analysis (EDA) and Feature Engineering (FE)

## 📋 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)** for the Black Friday dataset, which provides insights into customer shopping patterns. The data includes transaction details, customer demographics, and product information, making it a valuable resource for uncovering trends, understanding customer behavior, and generating features for further analytical and predictive work.

- **Objective**: Explore customer purchase behavior and engineer relevant features to extract actionable insights or prepare for predictive modeling.
- **Dataset**: The Black Friday dataset, available on Kaggle, contains details such as Age, Gender, City_Category, Product_ID, and Purchase Amount.

## 🔍 Exploratory Data Analysis (EDA)
This section involves analyzing the dataset to reveal patterns, relationships, and potential areas for feature engineering. Typical steps include:

- **Data Overview**: Provides an overview of the dataset, including customer demographics, product details, and purchase transactions. This dataset comprises approximately 500,000 rows.
- **Missing Values & Data Cleaning**: Identification and handling of any missing data, including potential outliers.
- **Distribution Analysis**: Exploring the distribution of key demographic and categorical variables (e.g., age groups, product categories) and analyzing numerical data (like purchase amounts) to identify trends.
- **Correlation Analysis**: Examining relationships between key features and purchase amounts. Visualizations such as heatmaps and scatter plots help identify relevant trends.

### Key Visualizations
- **Spending Patterns by Demographic**: Charts showing spending behavior by age group, gender, or city type.
- **Product Category Insights**: Analysis of popular product categories based on spending trends.
- **City-based Analysis**: Trends in spending patterns across different city categories (e.g., metro vs. non-metro).

## 🛠️ Feature Engineering (FE)
New features were engineered to enhance future analyses and predictive modeling capabilities. Common approaches include:

- **Spending Patterns**: Features that capture spending trends by customer demographic groups (e.g., age or city).
- **Customer Demographics**: Encoding categorical variables (e.g., Gender, City_Category) for improved model usability.
- **Product Interactions**: Creating features that capture the count or frequency of product categories each customer interacts with.
- **Frequency Encoding**: For variables with frequently appearing values (e.g., Product_ID, Occupation), frequency encoding can help capture significance.

## 📊 Results & Insights
The EDA and Feature Engineering phases provided valuable insights, such as:

- **High-Spending Demographics**: Identified groups, such as certain age ranges or city types, that tend to spend more.
- **Popular Product Categories**: Highlighted top categories by purchase amounts, pointing to popular items during Black Friday.
- **Influence of Gender & City**: Noted spending patterns based on demographic segments, useful for targeted marketing strategies.

These findings offer a strong foundation for customer segmentation, targeted promotions, and predictive modeling.

## 🚀 Getting Started
To explore this project on your machine:

1. Clone this repository.
2. Install required dependencies (if available) via `requirements.txt`.
3. Open and execute the Jupyter notebooks to replicate the EDA and feature engineering steps.

## 💡 Future Work
Potential next steps to expand this project include:

- **Predictive Modeling**: Train models to forecast purchase amounts or classify customer segments.
- **Advanced Feature Engineering**: Develop interaction or polynomial features to capture non-linear relationships.
- **Time-Series Analysis**: Analyze trends over time, if data allows, to predict future sales or seasonal patterns.

---
