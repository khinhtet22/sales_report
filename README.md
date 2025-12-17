# 📊 Sales Strategy Analysis & Business Insights

This project analyzes the performance of different sales methods for a newly launched office stationery product line.  
The goal is to **optimize revenue while balancing sales effort and efficiency**.

---

## 🧭 Business Context & Goals

<p align="center">
  <img src="images/business_context.png" width="800">
</p>

**Objectives**
- Optimize sales strategy for revenue and efficiency
- Understand customer reach and revenue distribution
- Identify trends and recommend the best sales approach

---

## 👥 Customer & Sales Overview

<p align="center">
  <img src="images/customers_sales_overview_1.png" width="800">
</p>

<p align="center">
  <img src="images/customers_sales_overview_2.png" width="800">
</p>

**Key observations**
- Email reached the largest number of customers
- Email + Call generated the highest revenue per customer
- Call-only method showed the lowest efficiency

---

## ⏱ Revenue & Number of Purchasers Over Time

<p align="center">
  <img src="images/revenue_purchasers_over_time.png" width="800">
</p>

**Insights**
- Email revenue started high but declined over time
- Email + Call showed steady revenue growth
- Call-only remained the lowest performer

---

## 📈 Additional Customer Insights (Tenure Analysis)

<p align="center">
  <img src="images/customer_insights.png" width="800">
</p>

**Findings**
- Purchases and revenue decline as customer tenure increases
- Newer customers respond more strongly to the new product line

---

## 📊 Revenue Distribution

<p align="center">
  <img src="images/revenue_distribution.png" width="800">
</p>

**Notes**
- Email + Call shows higher-value purchases
- Some outliers indicate occasional bulk purchases

---

## 🧪 Data Validation & Cleaning Summary

<p align="center">
  <img src="images/data_validation_cleaning.png" width="800">
</p>

**Data quality checks**
- 15,000 rows validated
- No duplicate customers
- No negative numerical values
- Sales method categories standardized
- Invalid tenure values removed

---

## ⚙️ Proposed Business Metric: Revenue per Hour (RPH)

<p align="center">
  <img src="images/proposed_business_metric.png" width="800">
</p>

**Metric definition**

> **Revenue per Hour of Sales Effort (RPH)**  
> = Total Revenue ÷ Total Sales Hours

This metric balances **revenue impact** with **team effort**.

---

## ⚖️ Sales Method Performance Comparison

<p align="center">
  <img src="images/sales_performance_scatter.png" width="800">
</p>

<p align="center">
  <img src="images/sales_performance_assumptions.png" width="800">
</p>

**Summary**
- **Email**: Highest RPH due to minimal time and broad reach
- **Email + Call**: Highest revenue per customer, strong growth potential
- **Call-only**: Lowest RPH, high time cost

---

## 🔍 Key Findings

<p align="center">
  <img src="images/key_findings.png" width="800">
</p>

- Email maximizes reach with minimal effort
- Email + Call increases customer value through personalization
- Call-only approach limits scalability

---

## ✅ Final Recommendations

<p align="center">
  <img src="images/final_summary_recommendations.png" width="800">
</p>

**Recommended strategy**
- Use **Email** for fast, wide customer reach
- Leverage **Email + Call** for high-value customers
- Discontinue **Call-only** outreach
- Focus on newer customers
- Track **Revenue per Hour (RPH)** weekly
- Use cross-sell and threshold promotions to increase AOV

---

## 🛠 Tools & Skills Used
- Python (Pandas, Matplotlib, Seaborn)
- Data Cleaning & Validation
- Exploratory Data Analysis (EDA)
- Business Metrics Design
- Data Visualization & Storytelling


# 🛍️ Product Sales Analysis Project

This project analyzes product sales data using **Python** to uncover business insights such as top-selling items, revenue trends, and profit performance.  
It demonstrates how to perform **data cleaning**, **exploratory data analysis (EDA)**, and **visualization** in a real-world sales scenario.
---

## ✅ Project Overview

The notebook performs end-to-end analysis on sales data.  
Key steps include:

1. **Data Loading** – Import the dataset using pandas.  
2. **Data Cleaning** – Handle missing values, remove duplicates, fix column types.  
3. **Exploratory Data Analysis (EDA)** – Generate summary statistics and identify key metrics.  
4. **Visualization** – Use Matplotlib/Seaborn to show trends and performance.  
5. **Insights & Recommendations** – Summarize findings for decision-making.

---

## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `practical_exam_sales_report.ipynb` | Main Jupyter Notebook with data cleaning, analysis & charts |
| `practical exam product sales report.pdf` | Original written report |
| `README.md` | Overview of the project and instructions |

---

## 🧰 Tools & Libraries Used

- **Python 3**
- **pandas** – data manipulation  
- **matplotlib / seaborn** – data visualization  
- **numpy** – numeric calculations  
- **Jupyter Notebook** – interactive analysis environment  

---

## 📊 Example Analysis Performed

- Total and average sales by product  
- Monthly or quarterly revenue trends  
- Profit margin calculation  
- Top 5 performing products  
- Sales distribution by region or category  
- Visualization of sales and profit trends  

---

## 🚀 How to Run the Project

1. Install Python 3 and Jupyter Notebook  
2. Clone or download this repository  
3. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn numpy
   ```
4. Open the notebook:
   ```bash
   jupyter notebook practical_exam_sales_report.ipynb
   ```
5. Run the notebook cells sequentially to view the full analysis  

---

## 💡 Future Improvements

- Automate monthly sales reporting  
- Add Power BI or Streamlit dashboard  
- Include predictive sales forecasting  
---

## ✍️ Author

**Name:** *Khin Htet*  
**Project Type:** Practical Exam / Sales Data Analysis  
**Language:** Python (Jupyter Notebook)  

---

⭐ *If you like this project, please give the repository a star on GitHub!*
