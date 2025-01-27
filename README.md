# eCommerce Data Science Assignment

This repository contains the solution to the Data Science assignment based on an eCommerce Transactions dataset. The task involves performing Exploratory Data Analysis (EDA), building a Lookalike Model, and applying Customer Segmentation/Clustering techniques to derive business insights and predictive models.

## Contents

- **FirstName_LastName_EDA.pdf**: PDF report with business insights derived from the Exploratory Data Analysis (EDA).
- **FirstName_LastName_EDA.ipynb**: Jupyter notebook containing the code for EDA.
- **FirstName_LastName_Lookalike.csv**: CSV file containing the top 3 lookalike customers with similarity scores for the first 20 customers.
- **FirstName_LastName_Lookalike.ipynb**: Jupyter notebook with the Lookalike Model code.
- **FirstName_LastName_Clustering.pdf**: PDF report summarizing the customer segmentation, including clustering metrics and visualizations.
- **FirstName_LastName_Clustering.ipynb**: Jupyter notebook with the clustering code.

## Overview

The dataset consists of three CSV files: `Customers.csv`, `Products.csv`, and `Transactions.csv`. The goal of the assignment is to analyze the data, build models, and generate actionable business insights.

### Dataset Description

#### **Customers.csv**
- **CustomerID**: Unique identifier for each customer.
- **CustomerName**: Name of the customer.
- **Region**: Continent where the customer resides.
- **SignupDate**: Date when the customer signed up.

#### **Products.csv**
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Product price in USD.

#### **Transactions.csv**
- **TransactionID**: Unique identifier for each transaction.
- **CustomerID**: ID of the customer who made the transaction.
- **ProductID**: ID of the product sold.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity of the product purchased.
- **TotalValue**: Total value of the transaction.
- **Price**: Price of the product sold.

## Tasks

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
- Perform EDA to understand the data structure and identify trends.
- Derive at least 5 business insights.
- Deliverables: Jupyter notebook for EDA, PDF report with insights.

### **Task 2: Lookalike Model**
- Build a Lookalike Model to recommend 3 similar customers based on their profiles and transaction history.
- Use both customer and product data.
- Output: A CSV file (`Lookalike.csv`) with customer recommendations and similarity scores for the first 20 customers.
- Deliverables: Jupyter notebook for the model.

### **Task 3: Customer Segmentation / Clustering**
- Perform customer segmentation using clustering techniques, utilizing both customer profile and transaction data.
- Choose clustering algorithms and determine the optimal number of clusters (between 2 and 10).
- Calculate clustering metrics, including the DB Index.
- Deliverables: Jupyter notebook for clustering, PDF report with metrics and visualizations.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/username/repository-name.git
