# **Data Science Intern Assignment: eCommerce Transactions Dataset**

## **Project Overview**
This project involves analyzing an eCommerce transactions dataset to perform **Exploratory Data Analysis (EDA)**, build a **Lookalike Model**, and perform **Customer Segmentation**. The dataset consists of three files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The goal is to derive actionable business insights, recommend similar customers, and segment customers based on their profiles and transaction history.

---

## **Files Description**
1. **Customers.csv**
   - `CustomerID`: Unique identifier for each customer.
   - `CustomerName`: Name of the customer.
   - `Region`: Continent where the customer resides.
   - `SignupDate`: Date when the customer signed up.

2. **Products.csv**
   - `ProductID`: Unique identifier for each product.
   - `ProductName`: Name of the product.
   - `Category`: Product category.
   - `Price`: Product price in USD.

3. **Transactions.csv**
   - `TransactionID`: Unique identifier for each transaction.
   - `CustomerID`: ID of the customer who made the transaction.
   - `ProductID`: ID of the product sold.
   - `TransactionDate`: Date of the transaction.
   - `Quantity`: Quantity of the product purchased.
   - `TotalValue`: Total value of the transaction.
   - `Price`: Price of the product sold.

---

## **Tasks**

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
- Perform EDA on the provided dataset.
- Derive at least **5 business insights** from the EDA.
- **Deliverables**:
  - A PDF report with business insights

### **Task 2: Lookalike Model**
- Build a Lookalike Model that recommends **3 similar customers** based on their profile and transaction history.
- The model should:
  - Use both customer and product information.
  - Assign a similarity score to each recommended customer.
- **Deliverables**:
  - A CSV file (`Lookalike.csv`) containing the top 3 lookalikes with similarity scores for the first 20 customers (CustomerID: C0001 - C0020).

### **Task 3: Customer Segmentation / Clustering**
- Perform **customer segmentation** using clustering techniques.
- Use both **profile information** (from `Customers.csv`) and **transaction information** (from `Transactions.csv`).
- **Deliverables**:
  - A report on clustering results, including the number of clusters, DB Index value, and other relevant metrics.
