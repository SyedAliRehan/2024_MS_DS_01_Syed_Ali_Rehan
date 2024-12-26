# 2024_MS_DS_01_Syed_Ali_Rehan
#Vedio Google drive link below (vedio is in 2 parts) , uploaded in google drive 
#Advance Techniques in Data science Project video link : https://drive.google.com/drive/folders/1WqCZaR-P5-9xSEFgbnd5cjACiLfPqCFV?usp=sharing 
 Marketplace Sales Data Analysis

### 1. Problem Definition and Objectives
#### **Problem Statement**:
Analyze supermarket sales data to uncover insights that help in understanding customer behavior, improving sales strategies, and making data-driven decisions for business growth.

#### **Objectives**:
- Identify trends and patterns in sales across branches, cities, and product categories.
- Predict future sales and evaluate factors influencing them.
- Support decision-making for optimizing operational and marketing strategies.

---

### 2. Questions Posed:
1. What are the key trends in sales distribution across branches and cities?
2. Which product categories and branches contribute the most to revenue?
3. How do customer demographics affect sales performance?
4. Can we predict sales using machine learning models?

---

### 3. Dataset:
The dataset appears to be a supermarket sales dataset containing:
- **Key Features**: Branch, city, product categories, sales amounts, taxes, customer types, payment methods, and more.
- **Target Variable**: Sales or revenue generated.

---

### 4. Dataset Relevance:
This dataset is highly relevant for:
- Understanding customer preferences and shopping habits.
- Analyzing sales performance by branch, city, or category.
- Predictive modeling for revenue forecasting.

---

### 5. Data Wrangling and Cleaning Steps Performed:
- **Null Value Handling**: Checked and addressed any missing data (`df.isnull().sum()`).
- **Duplicates Removal**: Removed duplicate rows (`df.duplicated().sum()`).
- **Data Types**: Verified and converted data types if necessary (`df.info()`).

---

### 6. Encoding Categorical Variables:
The notebook uses **Label Encoding** to convert categorical variables into numerical format, which is essential for feeding the data into machine learning models.

---

### 7. Exploratory Data Analysis (EDA):
- **Visualizations**: 
  - Distribution of sales across branches and cities using bar plots and histograms.
  - Revenue by product categories, payment methods, and customer types using pie charts.
- **Correlation Analysis**: Heatmaps to identify relationships between numerical variables.
- **Key Metrics**: Tax, total sales, and reward points analyzed for patterns.

---

### 8. Predictive Analysis:
- **Models Built**:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting
  - Decision Trees
  - Support Vector Regressor (SVR)
  - KNN Regressor
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R² Score

Linear Regression was identified as the best-performing model based on its low MSE and high R² score.

---

### 9. Key Insights:
- Branch and city-level performance varies significantly, with some locations generating higher sales.
- Specific product categories and customer types drive most of the revenue.
- Linear Regression outperformed other models for sales prediction.

---

### 10. Recommendations:
1. Focus marketing efforts on high-performing branches and product categories.
2. Use predictive insights to optimize inventory and resource allocation.
3. Improve customer engagement strategies based on demographic and behavioral data.

---

### 11. Conclusion:
The analysis successfully identified sales trends, key factors influencing revenue, and provided actionable insights. Predictive models validated the potential for forecasting sales, aiding in data-driven decision-making.

