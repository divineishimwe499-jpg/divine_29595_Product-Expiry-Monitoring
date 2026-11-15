# divine_29595_Product-Expiry-Monitoring
# Product-Expiry-Monitoring

Student Name:ISHIMWE Divine  
Student ID:29595  
Technology: Oracle Database and PL/SQL

1. Problem Statement

 Businesses dealing with perishable and time sensitive products often experience financial losses due to poor expiry-date monitoring, delayed stock rotation, and failure to identify products at risk of expiring. Manual monitoring makes it difficult to track individual product batches, prioritize sales, and take timely action before products become unsellable.

2. Project Objectives

- To develop a centralized system for monitoring product expiry at batch level.
- To identify products at risk of expiring before their expiry dates.
- To automate stock prioritization using the First Expiry, First Out (FEFO) approach.
- To prevent expired products from being sold.
- To monitor and report financial losses associated with expired stock.

3. Data Sources

 Kaggle
 UCI Repository
 Google Dataset Search or HDX

4. Planned Innovation

ExpiryGuard: Automated Expiry Risk Classification and Loss Prevention.

The system will automatically classify products into expiry risk categories based on their remaining shelf life, prioritize batches using FEFO, prevent expired product sales, and calculate the estimated financial value of stock at risk. Scheduled expiry checks and an interactive dashboard will help businesses take action before losses occur.

5. Planned Database Tables

1.PRODUCTS: Stores product information.
2.CATEGORIES: Manages product classifications.
3.SUPPLIERS: Stores supplier details.
4.PRODUCT BATCHES: Tracks batch numbers, quantities, and expiry dates.
5.STOCK MOVEMENTS: Records stock received, sold, and removed.
6.SALES: Stores sales transactions.
7.EXPIRY ALERTS: Records expiry warnings and actions taken.

6. Planned PL/SQL Features

- Procedures: Register products, receive batches, and process sales.
- Functions: Calculate remaining shelf life and estimated stock loss.
- Triggers: Prevent expired product sales and automatically update stock.
- Cursors: Generate batch-level expiry and stock reports.
- Sequences: Generate unique record identifiers.
- Exception Handling: Prevent invalid transactions and incorrect records.
- DBMS SCHEDULER: Run automatic expiry checks at scheduled intervals.



#7. References

 1. Kaggle (Retail Food Package Expiry Date Dataset)  https://www.kaggle.com/datasets/ziya07/retail-food-package-expiry-date-dataset
 2. Kaggle (Grocery Inventory and Sales Dataset with Expiration Dates)  https://www.kaggle.com/datasets/salahuddinahmedshuvo/grocery-inventory-and-sales-dataset
 3. UCI Machine Learning Repository (Stock Keeping Units Shelf-Life & Outbound Data)  https://archive.ics.uci.edu/ml/datasets/Stock+keeping+units
 4. Google Dataset Search (Product Expiry & Shelf Life Search Portal)  google.com
 5. Humanitarian Data Exchange (HDX) (Data Portal & Supply Chain Datasets)  https://data.humdata.org/
