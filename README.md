# Customer Segmentation Using RFM Analysis

## 📌 Project Overview
This project performs **customer segmentation** analysis using the **RFM (Recency, Frequency, Monetary)** model on a real-world retail dataset. The analysis aims to identify high-value and at-risk customers and provide actionable business recommendations to improve customer retention and overall revenue.

---

## 📂 Dataset

- **Name:** Online Retail Dataset  
- **Source:** Kaggle  
- **URL:** https://www.kaggle.com/datasets/ulrikthygepedersen/online-retail-dataset  
- **Description:**  
  The dataset contains transactions from a UK-based online retail store. It includes information about invoice numbers, products, quantities, prices, customer IDs, and countries of purchase.

**Columns used in this project:**

| Column | Description |
|--------|-------------|
| InvoiceNo | Unique identifier for each transaction |
| StockCode | Product/code identifier |
| Description | Product name/description |
| Quantity | Quantity of items purchased |
| InvoiceDate | Date and time of transaction |
| UnitPrice | Price per item |
| CustomerID | Unique identifier for each customer |
| Country | Country of the customer |

---

## 🛠️ Tools & Technologies

The following tools and libraries were used in this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Project Workflow

The project involves several key steps:

1. **Data Loading & Cleaning**  
   Handling missing values, correcting data types, and ensuring only valid transactions are analyzed.

2. **Feature Engineering**  
   Creating a new column (`TotalPrice`) to represent the total revenue per transaction.

3. **Exploratory Data Analysis (EDA)**  
   Understanding key metrics such as revenue distribution by country and best-selling products.

4. **RFM Calculation**  
   Calculating Recency, Frequency, and Monetary values for every customer.

5. **Customer Segmentation**  
   Segmenting customers into meaningful groups using RFM scores.

6. **Visualization**  
   Creating charts to visualize segment distribution and revenue contribution.

7. **Insight Extraction & Business Recommendations**  
   Interpreting results and providing strategies based on data insights.

---

## 📈 Key Insights

- A small number of customers contribute the largest share of revenue.
- Customers with high RFM scores are valuable and should be retained with loyalty programs.
- Customers identified as “At Risk” require re-engagement strategies to prevent churn.

---

## 💡 Business Recommendations

Based on the RFM analysis:

- **Champions:** Offer exclusive rewards to retain top customers.
- **Loyal Customers:** Encourage repeat purchases with targeted promotions.
- **Potential Loyalists:** Nurture with personalized offers to increase engagement.
- **At Risk:** Prioritize reactivation campaigns to bring customers back.
- **Lost Customers:** Use targeted messaging to identify and win back customers where feasible.

---

## 🚀 How to Run

1. Clone this repository or download the ZIP.
2. Open `customer_segmentation_rfm.ipynb` using Jupyter Notebook.
3. Download online_retail csv from kaggle.
4. Run all cells from top to bottom to reproduce the analysis.

