eCommerce Transactions Dataset - Data Science Assignment
Overview

This project is centered around an eCommerce Transactions dataset and involves tasks like Exploratory Data Analysis (EDA), predictive modeling, and clustering for business insights and customer segmentation. The dataset consists of three files: Customers.csv, Products.csv, and Transactions.csv.

The project aims to evaluate the candidate's skills in:

    Analyzing and extracting insights from data.
    Building predictive models.
    Applying clustering techniques for customer segmentation.

Dataset Description
1. Customers.csv

    CustomerID: Unique identifier for each customer.
    CustomerName: Name of the customer.
    Region: Continent where the customer resides.
    SignupDate: Date of customer signup.

2. Products.csv

    ProductID: Unique identifier for each product.
    ProductName: Name of the product.
    Category: Product category.
    Price: Product price in USD.

3. Transactions.csv

    TransactionID: Unique identifier for each transaction.
    CustomerID: ID of the customer who made the transaction.
    ProductID: ID of the product sold.
    TransactionDate: Date of the transaction.
    Quantity: Quantity of the product purchased.
    TotalValue: Total transaction value.
    Price: Price of the product sold.

Project Tasks
Task 1: Exploratory Data Analysis (EDA) and Business Insights

    Perform EDA on the dataset to uncover trends and patterns.
    Derive at least 5 business insights, focusing on actionable recommendations.
    Deliverables:
        A Jupyter Notebook with the EDA code.
        A PDF report summarizing the insights.

Task 2: Lookalike Model

    Build a Lookalike Model to recommend 3 similar customers for each user based on their profile and transaction history.
    Use both customer and product information to assign similarity scores.
    Deliverables:
        A Lookalike.csv file with mappings of customer IDs and similarity scores for the first 20 customers (CustomerID: C0001 - C0020).
        A Jupyter Notebook with the model code.

Task 3: Customer Segmentation (Clustering)

    Perform clustering to segment customers using their profile and transaction information.
    Evaluate clusters with metrics like the DB Index and visualize the results.
    Deliverables:
        A PDF report detailing the clustering results, including:
            Number of clusters formed.
            DB Index value.
            Other metrics.
        A Jupyter Notebook with the clustering code.

Submission Instructions

    Upload all files to a public GitHub repository.
    Ensure your files follow the naming convention:
        EDA Report: FirstName_LastName_EDA.pdf
        EDA Code: FirstName_LastName_EDA.ipynb
        Lookalike Model Output: FirstName_LastName_Lookalike.csv
        Lookalike Model Code: FirstName_LastName_Lookalike.ipynb
        Clustering Report: FirstName_LastName_Clustering.pdf
        Clustering Code: FirstName_LastName_Clustering.ipynb

Evaluation Criteria

    Exploratory Data Analysis: 25%
    Business Insights: 15%
    Lookalike Model: 30%
    Customer Segmentation: 30%

Notes:

    Ensure code clarity and efficiency.
    Provide meaningful and actionable insights.
    Follow the naming and formatting conventions strictly to avoid disqualification.

Tools and Libraries

This project is implemented in Python using the following libraries:

    Pandas
    NumPy
    Matplotlib/Seaborn
    Scikit-learn