# 📊 Sales Performance Analysis & Dashboard

### 🚀 Overview
This project involves a comprehensive analysis of a retail sales dataset containing over **10,000 transaction records**. Using **Python**, I transformed raw data into actionable business insights, focusing on performance metrics across different regions, time periods, and product lines.

The goal of this project is to demonstrate an end-to-end data analytics workflow: from **Data Cleaning** and **Feature Engineering** to **Statistical Analysis** and **Visualization**.

### 🛠️ Technologies Used
* **Python 3.11**
* **Pandas:** For data manipulation, aggregation, and cleaning.
* **NumPy:** For numerical operations.
* **Matplotlib & Seaborn:** For creating static, publication-quality visualizations.
* **Jupyter Notebook:** For interactive development.

---

### 📂 Dataset Structure
The analysis is based on `Sales_Data.csv`, which contains the following key features:
* `Date`: Transaction date (Time-series data).
* `Region` / `State` / `City`: Geographical data for spatial analysis.
* `Product`: Item SKU/Name.
* `Units` & `Price`: Quantity sold and unit price.
* `Total Sales`: The target revenue metric.
* `SalesRep`: Employee performance data.

---

### ⚙️ Methodology & Analysis Workflow

#### 1. Data Cleaning & Preprocessing
* **Handling Missing Values:** Detected null values in `Units` and `Total Sales` columns and imputed them using the **mean** strategy to maintain statistical distribution.
* **Data Type Conversion:** Converted the `Date` column to `datetime` objects to enable time-series analysis.
* **Duplicate Removal:** Identified and removed duplicate records to ensure data integrity.

#### 2. Feature Engineering
* Extracted **Month** and **Month Name** from the `Date` column to allow for seasonality analysis.
* Created specific time-series features to analyze Quarter-over-Quarter (QoQ) growth.

#### 3. Exploratory Data Analysis (EDA)
* **Regional Analysis:** Grouped data by `Region` to identify the strongest markets.
* **Product Performance:** Aggregated sales by `Product` to find top-performing SKUs.
* **Temporal Trends:** Analyzed sales distribution over Quarters (`Qtr`) and Months to detect seasonality spikes.
* **Correlation Analysis:** Generated a **Heatmap** to understand the relationship between `Units`, `Price`, and `Total Sales`.

---

### 💡 Key Insights

1.  **Regional Dominance:**
    * The **North Region** is the top performer, generating over **3.6M** in sales, followed closely by the West.
    * **Delhi** appears as the highest-grossing city individually.

2.  **Product Trends:**
    * The top-selling product is **"Nestle Smarties Pop-Up"**, generating ~1.5M in revenue.
    * Low-performing products were identified for potential inventory review.

3.  **Seasonality:**
    * **Q3 (Quarter 3)** showed an exceptional spike in sales (**~7.7M**), significantly outperforming all other quarters combined.
    * **December** and **November** are the strongest months, indicating a heavy holiday season influence.

---


---

### 💻 How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/sales-analysis-python.git](https://github.com/yourusername/sales-analysis-python.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn openpyxl
    ```
3.  **Run the Notebook:**
    Launch Jupyter and open `Final_project.ipynb`.

---

### 👨‍🏫 About the Author
**Govinda Upadhyay**
*Python Educator & Data Analyst*

I specialize in teaching Python for Data Science and building automated analysis pipelines. I enjoy breaking down complex datasets to find the "story" behind the numbers.

[LinkedIn Profile] | [Portfolio Website]
