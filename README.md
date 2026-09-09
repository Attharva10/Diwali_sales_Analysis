# Diwali_sales_Analysis

# 🪔 Diwali Sales Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4c72b0)

## 📌 Project Overview

This project focuses on analyzing **Diwali sales data** to understand customer purchasing behavior, sales patterns, and product preferences during the festive season.

The analysis uses **Python and Jupyter Notebook** to perform data cleaning, exploratory data analysis (EDA), and data visualization.

The main goal is to transform raw sales data into meaningful insights that can help businesses understand their customers and make better decisions regarding **marketing, product demand, and inventory planning**.

---

## 🎯 Objectives

The key objectives of this project are:

* Clean and prepare the raw Diwali sales dataset.
* Explore customer demographics and purchasing behavior.
* Analyze sales based on different customer attributes.
* Identify high-performing product categories.
* Understand purchasing patterns across different states.
* Analyze sales by gender, age group, occupation, and marital status.
* Visualize important trends and relationships in the data.
* Generate actionable business insights from the analysis.

---

## 📊 Dataset

The project uses a Diwali sales dataset containing information about customers and their purchases.

The dataset contains attributes related to:

### Customer Information

* Gender
* Age
* Age Group
* Marital Status
* State
* Occupation

### Purchase Information

* Product Category
* Product ID
* Purchase Amount
* Orders

The raw dataset is available in the repository as:

```text
Diwali Sales Data.csv
```

---

## 🛠️ Technologies Used

The following technologies and Python libraries are used in this project:

| Technology       | Purpose                        |
| ---------------- | ------------------------------ |
| Python           | Data analysis and programming  |
| Jupyter Notebook | Interactive analysis           |
| Pandas           | Data cleaning and manipulation |
| NumPy            | Numerical operations           |
| Matplotlib       | Data visualization             |
| Seaborn          | Statistical visualization      |

---

## 📁 Project Structure

```text
Diwali_sales_Analysis/
│
├── Diwali Sales Data.csv
│
├── Diwali_Sales_Analysis_project.ipynb
│
└── README.md
```

### Files Description

**`Diwali Sales Data.csv`**

Raw Diwali sales dataset used for the analysis.

**`Diwali_Sales_Analysis_project.ipynb`**

Main Jupyter Notebook containing the complete data cleaning, exploratory analysis, visualizations, and insights.

**`README.md`**

Project documentation and overview.

---

## 🔍 Data Analysis Process

The project follows a typical data analysis workflow.

### 1. Data Loading

The dataset is imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("Diwali Sales Data.csv")
```

---

### 2. Data Understanding

The dataset is inspected to understand:

* Number of rows and columns
* Data types
* Column names
* Missing values
* Duplicate records
* Basic statistical information

Example:

```python
df.head()
df.shape
df.info()
df.describe()
```

---

### 3. Data Cleaning

The raw dataset is cleaned before performing the analysis.

The cleaning process includes:

* Identifying missing values
* Removing unnecessary columns
* Checking duplicate records
* Correcting data types
* Handling invalid or inconsistent values

Example:

```python
df.isnull().sum()
df.drop_duplicates(inplace=True)
```

---

### 4. Exploratory Data Analysis

EDA is performed to understand relationships between customer characteristics and sales.

The analysis explores:

* Gender-wise purchasing
* Age-group-wise purchasing
* State-wise sales
* Occupation-wise sales
* Marital-status-wise sales
* Product-category-wise sales
* Purchase amount distribution

---

## 📈 Visualizations

The project uses visualizations to make the analysis easier to understand.

Some of the analysis includes:

### 👥 Gender Analysis

Compare purchasing behavior between different genders.

### 🎂 Age Group Analysis

Identify which age groups contribute most to sales.

### 🗺️ State-wise Analysis

Analyze customer purchases across different states.

### 💼 Occupation Analysis

Understand purchasing patterns based on customers' occupations.

### 💍 Marital Status Analysis

Analyze sales according to marital status.

### 🛍️ Product Category Analysis

Identify popular product categories and understand product demand.

---

## 💡 Key Insights

The analysis helps identify patterns such as:

* Which customer groups contribute significantly to sales.
* Which age groups have higher purchasing activity.
* Which states generate more orders or sales.
* Which occupations represent valuable customer segments.
* Which product categories are more popular.
* How customer demographics are related to purchasing behavior.

These insights can be used to improve **targeted marketing campaigns, inventory planning, and customer segmentation**.

---

## 📌 Business Recommendations

Based on the analysis, businesses can:

### 1. Target High-Value Customer Segments

Marketing campaigns can focus on customer groups with higher purchasing activity.

### 2. Improve Inventory Planning

Popular product categories can be stocked in higher quantities before the Diwali season.

### 3. Create Targeted Marketing Campaigns

Customer demographics such as age, gender, occupation, and location can be used to create more relevant campaigns.

### 4. Focus on High-Performing Regions

Businesses can prioritize regions that demonstrate stronger purchasing activity.

### 5. Personalize Offers

Customer segments can be targeted with personalized discounts and promotional offers based on their purchasing behavior.

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/Attharva10/Diwali_sales_Analysis.git
```

### Step 2: Open the Project

```bash
cd Diwali_sales_Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open:

```text
Diwali_Sales_Analysis_project.ipynb
```

Run the notebook cells sequentially to reproduce the analysis.

---

## 🚀 Skills Demonstrated

This project demonstrates practical knowledge of:

* Python
* Pandas
* NumPy
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Customer Segmentation
* Business Insight Generation

---

## 📷 Project Visualizations

You can add screenshots of your important charts here.

For example:

```markdown
![Gender Analysis](images/gender_analysis.png)
![Age Group Analysis](images/age_group_analysis.png)
![State Analysis](images/state_analysis.png)
![Product Category Analysis](images/product_category_analysis.png)
```

If you create an `images` folder, you can place your exported charts there.

---

## 🔮 Future Improvements

Possible improvements to this project include:

* Create an interactive dashboard using Power BI or Tableau.
* Perform deeper customer segmentation.
* Add SQL-based analysis.
* Build automated data-cleaning pipelines.
* Analyze sales trends in more detail.
* Add additional business KPIs.
* Deploy the analysis as an interactive web application.

---

## 🤝 Contributing

Contributions are welcome.

If you would like to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push the branch.
6. Create a Pull Request.

---

## 👨‍💻 Author

**Atharva**

GitHub:
https://github.com/Attharva10

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is available for educational and portfolio purposes.
