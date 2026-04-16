# Retail-Customer-Insights-EDA-
An exploratory data analysis (EDA) project focused on uncovering consumer spending patterns and retail trends. By standardizing messy transactional data, this study visualizes the impact of loyalty programs on purchase frequency to inform targeted marketing strategies. Developed using Pandas, Matplotlib, and Seaborn.
---

## 🎯 Objective
- To analyze customer distribution across different cities and age groups.
- To evaluate the total purchase amount across genders and geographic locations.
- To examine the correlation between loyalty program membership and customer ratings.
- To determine the average spending patterns based on customer income and age.

---

## 🛠 Tools & Technologies
- **Python**
- **Pandas** – data cleaning & manipulation  
- **Matplotlib & Seaborn** – data visualization  
- **Jupyter Notebook** – analysis & documentation

---

## 🧠 Features Used for Prediction

| Feature     | Description |
|-------------|-------------|
| `age`       | Age of the customer. |
| `gender` | Gender of the subscriber (Male, Female, Other). |
| `annual_income` | Yearly income of the customer (standardized to numeric). |
| `purchase_amount`    | Total amount spent by the customer. |
| `purchase_date`  | Date of the transaction (standardized to datetime format). |
| `city`  | City where the customer is located (e.g., Mumbai, Delhi, etc.). |
| `product_category`    | Category of the purchased item (Electronics, Home, Clothing). |
| `rating`   | Customer satisfaction score (on a scale of 1-5). |
| `loyalty_member`   | Binary indicator (1 for Yes, 0 for No) of loyalty program membership. |

---

## 🔧 Data Preparation & Feature Engineering
- Handled missing and inconsistent data  
- Converted date columns into datetime format
- Created new features:
  - **age_group**
 
---

## 📈 Key Analysis Performed
- Identified Mumbai as the city with both the highest number of purchases and the highest total sum of purchases.
- Determined that Kolkata has the highest average annual income among customers.
- Cleaned the rating column by removing "/5" strings and replacing missing values with the median rating.

---

## 📊 Visualizations
The project includes clear and informative visualizations such as:
- Categorical Frequency Plots: Using df['city'].value_counts() and df['product_category'].value_counts() to see the distribution of customers across cities and categories.

- Bar Charts / Count Plots: A count plot is explicitly generated for the city column using sns.countplot() to visualize the number of customers in each city.

- Income Analysis: Calculations for the sum of purchase_amount by gender suggest intended comparative visualizations for spending patterns.

---

## 🧠 What This Project Demonstrates
- Perform Advanced Data Wrangling
- Apply Statistical Imputation
- Extract Business Intelligence
- Technical Proficiency

  ---

  ## 👤 Author

**Hamiz Ansari**
- **GitHub:** [github.com/hamiz-21-7-06](https://github.com/hamiz-21-7-06)
- **Email:** [hamizansari06@gmail.com](mailto:hamizansari06@gmail.com)
