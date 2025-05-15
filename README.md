# EDA-Balck-Friday-Sales
# 🛍️ Black Friday Sales Data Analysis

Black Friday is a shopping holiday that takes place the day after Thanksgiving, known for deep discounts on a wide range of products like electronics, home goods, and clothing. Retailers offer special deals and extended hours, making it one of the busiest shopping days of the year.

This project explores the **Black Friday Sales Data** to uncover purchasing patterns and insights from various user demographics. The dataset includes information such as age, gender, occupation, marital status, and product purchases made during the Black Friday sales event.

---

## 📌 Project Goals

- Perform Exploratory Data Analysis (EDA) on the Black Friday Sales dataset.
- Understand the impact of demographics on purchasing behavior.
- Visualize patterns and trends using Python data visualization libraries.
- Derive actionable insights by analyzing individual columns and multi-column combinations.

---

## 📂 Dataset Details

- **Dataset Name**: Black Friday Sales Data
- **Size**: 23 MB (CSV)
- **Records**: 537,000+ rows, 12 columns
- **Features**:
  - User_ID, Product_ID
  - Gender, Age, Occupation
  - City_Category, Stay_In_Current_City_Years
  - Marital_Status, Product_Category_1/2/3
  - Purchase (amount spent)

---

## 🔧 Prerequisites

To run this project, ensure you're familiar with:

- **Python**: Basic programming
- **Pandas**: Data manipulation
- **Matplotlib & Seaborn**: Data visualization
- **Jupyter Notebook**: Running Python code interactively
- **EDA Concepts**: Cleaning, inspecting, and analyzing data

---

## 📊 Project Steps Overview

### 1. Walkthrough of the Dataset
- Load the dataset using Pandas.
- Inspect structure using `.info()`, `.head()`, and `.isnull()`.
- Understand column types and check for missing values.

### 2. Analyzing Columns
- Focus on key columns: `Gender`, `Age`, `Marital_Status`, `Product_Category_1`, and `Purchase`.
- Drop sparse columns: `Product_Category_2`, `Product_Category_3`.
- Use `unique()` and `nunique()` for overview insights.

### 3. Gender-Based Analysis
- Identify gender imbalance (more male shoppers).
- Use `groupby()` to evaluate purchase distribution by gender.

### 4. Age & Marital Status
- Segment customers by age groups and marital status.
- Analyze which demographic groups spend more.

### 5. Multi-Column Analysis
- Combine `Age`, `Gender`, and `Marital_Status` to assess complex patterns.
- Visualize with bar and pie charts for deeper insight.

### 6. Occupation & Product Categories
- Explore how occupation affects purchase behavior.
- Identify product preferences across job roles.

### 7. Gender & Marital Status Combined
- Visualize with Seaborn `countplot` to understand the combined effect.
- Discover purchase trends based on user profiles.

---

## 📌 Conclusion

This analysis uncovers meaningful patterns in Black Friday purchase behavior:

- Male customers dominate purchases.
- Age and marital status influence buying patterns.
- Certain occupations are more likely to spend heavily.
- Combining demographic factors reveals deeper insights.

By cleaning, analyzing, and visualizing the data, we can better understand customer behavior during high-volume sales events and help businesses target the right audience more effectively.

---

## 💡 Tools Used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📬 Contact

For feedback or collaboration opportunities, feel free to connect:

- 📧 seshapugeetha@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/geetha-seshapu/)

