# 🪔 Diwali Sales Data Analysis

> **Exploratory Data Analysis of Diwali Sales Data using Python**

This project performs an **Exploratory Data Analysis (EDA)** on Diwali sales data to understand customer demographics, purchasing behavior, sales patterns, occupations, states, and product categories.

---

## 📌 Project Overview

The main objective of this project is to **clean, analyze, and visualize** the Diwali sales dataset and identify meaningful patterns in customer purchasing behavior.

The analysis focuses on understanding:

* 👥 Customer demographics
* 🛍️ Purchasing behavior
* 💰 Sales patterns
* 🌍 State-wise performance
* 💼 Occupation-wise purchasing
* 🛒 Product category performance

---

## 🛠️ Tools & Technologies

| Tool                    | Purpose                   |
| ----------------------- | ------------------------- |
| 🐍 **Python**           | Data analysis             |
| 🐼 **Pandas**           | Data manipulation         |
| 🔢 **NumPy**            | Numerical operations      |
| 📊 **Matplotlib**       | Data visualization        |
| 🎨 **Seaborn**          | Statistical visualization |
| 📓 **Jupyter Notebook** | Analysis environment      |

---

## 🔍 Analysis Performed

The project covers the following areas:

### 🧹 Data Cleaning

* Inspected the dataset
* Handled missing values
* Removed unnecessary columns
* Converted data types where required

### 👤 Customer Analysis

* Gender-wise analysis
* Age-group analysis
* Marital-status analysis
* Occupation-wise analysis

### 🌍 Geographical Analysis

* State-wise number of orders
* State-wise sales analysis

### 🛍️ Product Analysis

* Product-category analysis
* Top products based on number of orders

### 📊 Statistical Analysis

* Descriptive statistics
* Distribution and purchasing behavior analysis

---

## 📊 Key Insights

Based on the analysis:

* 👩 **Female customers** represent a larger share of buyers and contribute significantly to purchasing value.
* 🎯 The **26–35 age group** has the highest number of buyers.
* 🌍 **Uttar Pradesh, Maharashtra, and Karnataka** contribute the most orders.
* 💍 **Married women** represent an important customer segment with high purchasing value.
* 💼 Customers working in **IT, Aviation, and Healthcare** are among the major buyer groups.
* 🛒 **Food, Clothing, and Electronics** are among the most frequently purchased product categories.

---

## 🧹 Data Cleaning

The dataset was prepared through the following steps:

1. Removed unnecessary columns such as `Status` and `unnamed1`.
2. Checked the dataset for missing values.
3. Removed rows where `Amount` was missing.
4. Converted the `Amount` column from `float` to `integer`.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/kunal-kashyap635/EDA_ON_Diwali_Dataset.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd EDA_ON_Diwali_Dataset
```

### 3️⃣ Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4️⃣ Start Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
EDA(1).ipynb
```

and run the cells.

> 💡 **Note:** Make sure `Diwali Sales Data.csv` is present in the same directory as the notebook.

---

## 📁 Project Structure

```text
EDA_ON_Diwali_Dataset/
│
├── 📓 EDA(1).ipynb
├── 📊 Diwali Sales Data.csv
└── 📄 README.md
```

---

## 💡 Conclusion

The analysis shows that **married women in the 26–35 age group** form an important customer segment. Customers from **Uttar Pradesh, Maharashtra, and Karnataka**, along with buyers working in fields such as **IT, Healthcare, and Aviation**, contribute significantly to the sales observed in the dataset.

Among the analyzed categories, **Food, Clothing, and Electronics** are key product categories based on purchasing activity.

This project demonstrates how **Python-based EDA can be used to transform raw sales data into meaningful business insights.**

---

## 👨‍💻 Author

**Kunal Kashyap**

📌 GitHub:
https://github.com/kunal-kashyap635

---

⭐ **If you found this project useful, consider giving the repository a star!**
