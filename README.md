# Data-Science-Assignment-eCommerce-Transactions-Dataset-
eCommerce Transactions Dataset

The purpose of this project is to analyze the eCommerce transaction data in order to make conclusions regarding customer behavior – some of the core tasks involve: 

1. **Exploratory Data Analysis (EDA)**: 

   - Join and load customer, product and transaction datasets;

   - Examine Top products, transaction data with respect to time and regions, and customer behavior.

2. **Lookalike Model**: 

   - Use cosine similarity to recommend other customers with similar behavior.

3. **Customer Segmentation**: 

   - Use KMeans clustering to classify customers into different clusters based on their purchasing patterns.

   - Validate and analyze the clustering results using the Davies-Bouldin index, and plot the clusters.

# Datasets:

This project uses the following datasets:

- `Customers.csv`: Information about customers including `CustomerID`, `FirstName`, `LastName`, and `Region`.
- `Products.csv`: Product details such as `ProductID`, `ProductName`, and `Price`.
- `Transactions.csv`: Transaction data including `TransactionID`, `CustomerID`, `ProductID`, `Quantity`, `TotalValue`, and `TransactionDate`.

