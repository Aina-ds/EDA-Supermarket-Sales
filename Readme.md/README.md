# 🛒 Supermarket Sales Exploratory Data Analysis

## 📖 Project Overview

This project presents an **Exploratory Data Analysis (EDA)** of a supermarket sales dataset using **Python**. The objective is to explore customer purchasing behavior, identify sales trends, evaluate product performance, and generate actionable business insights through data visualization and statistical analysis.

The project demonstrates the complete EDA workflow, including data loading, data quality assessment, feature engineering, visualization, and business insight generation.

---

## 💼 Business Problem

Retail businesses generate large volumes of transactional data every day. Without proper analysis, valuable insights about customer behavior, product performance, and sales trends remain hidden.

This project aims to analyze supermarket sales data to answer important business questions such as:

- Which branch generates the highest sales?
- Which product lines contribute the most revenue?
- Do member customers spend more than normal customers?
- Which payment methods are preferred by customers?
- How do sales vary across different months?

The insights from this analysis can help businesses improve inventory planning, marketing strategies, and customer satisfaction.

---

## 🎯 Project Objectives

- Explore and understand the supermarket sales dataset.
- Assess data quality by checking for missing values and duplicates.
- Clean and preprocess the data.
- Create additional time-based features for analysis.
- Analyze customer purchasing behavior.
- Visualize sales trends using different charts.
- Generate meaningful business insights from the data.

---

## 📂 Dataset Information

**Dataset:** Supermarket Sales Dataset

The dataset contains transactional information collected from supermarket branches, including customer demographics, product categories, payment methods, and sales information.

### Dataset Summary

- **Rows:** 1,000
- **Columns:** 20
- **File Format:** CSV

### Key Features

- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Sales
- Payment Method
- Customer Rating
- Date

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git
- GitHub

---

## 📁 Repository Structure

```text
EDA-Supermarket-Sales/

├── Data/
│   ├── SuperMarket Analysis.csv
│   └── Supermarket_Sales_Cleaned1.csv
│
├── Notebooks/
│   └── Supermarket_Sales_EDA.ipynb
│
├── images/
│
├── LICENSE
│
└── README.md
```

---

## 🔄 Project Workflow

### 1️⃣ Import Required Libraries

The following libraries were used:

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

### 2️⃣ Data Loading

- Loaded the supermarket sales dataset into a Pandas DataFrame.
- Displayed sample records to understand the dataset structure.

---

### 3️⃣ Data Understanding

Performed an initial exploration by:

- Viewing sample records
- Checking data types
- Reviewing dataset information
- Generating descriptive statistics

---

### 4️⃣ Data Quality Assessment

Checked the dataset for:

- Missing values
- Duplicate records

**Results**

- ✅ No missing values
- ✅ No duplicate records

---

### 5️⃣ Data Cleaning & Feature Engineering

The following preprocessing steps were performed:

- Converted the **Date** column into datetime format.
- Extracted:
  - Month
  - Day
  - Year

These features were used for time-based sales analysis.

---

### 6️⃣ Exploratory Data Analysis

The following analyses were performed:

- 📊 Total Sales by Branch
- 📈 Monthly Sales Trend
- 🛍️ Total Sales by Product Line
- 👥 Sales by Customer Type
- 🚻 Sales by Gender
- 💳 Payment Method Distribution
- ⭐ Average Customer Rating by Branch

---

## 📊 Visualizations

The project includes multiple visualizations to better understand business performance, including:

- Bar Charts
- Line Charts
- Pie Charts
- Sales Comparisons
- Customer Rating Analysis

---

## 💡 Key Business Insights

The analysis revealed several valuable insights:

- One supermarket branch generated significantly higher total sales than the others.
- Certain product lines contributed the largest share of overall revenue.
- Member customers spent more than normal customers.
- Cash was the most frequently used payment method.
- Monthly sales varied across the three-month period, providing useful information for inventory planning.

---

## ✅ Results

This project successfully:

- Performed comprehensive exploratory data analysis.
- Cleaned and prepared the dataset.
- Created informative visualizations.
- Identified important customer purchasing patterns.
- Generated business insights for decision-making.
- Exported the cleaned dataset for future analysis.

---

## 🚀 Future Improvements

Possible enhancements include:

- Build a sales forecasting model using Machine Learning.
- Develop an interactive dashboard using Power BI or Tableau.
- Perform customer segmentation using clustering algorithms.
- Analyze seasonal sales patterns using larger datasets.
- Create automated business reports.

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/Aina-ds/EDA-Supermarket-Sales.git
```

### Navigate to the project

```bash
cd EDA-Supermarket-Sales
```

### Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Open the notebook

Launch Jupyter Notebook and open:

```
Notebooks/Supermarket_Sales_EDA.ipynb
```

Run all cells to reproduce the complete analysis.

---

## 📸 Sample Visualizations

Store your exported charts inside the **images/** folder and display them here.

Example:

```markdown
![Sales by Branch](images/sales_by_branch.png)

![Monthly Sales Trend](images/monthly_sales_trend.png)

![Payment Method Distribution](images/payment_distribution.png)
```

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Aina Azhar**

🎓 BS Data Science Student (6th Semester)

🏫 COMSATS University Islamabad

📍 Islamabad, Pakistan

💼 LinkedIn: https://www.linkedin.com/in/aina-azhar-a29a8b34a/

📧 Email: ainaazhar2019@gmail.com

⭐ If you found this project helpful, consider giving it a ⭐ on GitHub!
