eCommerce Data Science 


Task 1: Exploratory Data Analysis (EDA)

Load and clean the datasets.
Analyze:
Distribution of customers by region.
Popular product categories and their sales performance.
Trends in transaction data (e.g., sales over time).
Identify top customers by total spend.
Patterns in product pricing and quantity sold.
Derive 5 business insights.

Task 2: Lookalike Model

Combine customer and transaction data.
Engineer features for profile similarity (e.g., average spend, preferred categories).
Use similarity measures (e.g., cosine similarity, KNN) to find the top 3 lookalikes for the first 20 customers.
 Building a Lookalike Model. Here's the plan:

Feature Engineering:

Combine customer and transaction data.
Calculate features such as:
Total spend per customer.
Average transaction value.
Preferred product categories.
Similarity Calculation:

Use cosine similarity or a similar distance metric to find the top 3 most similar customers for each target customer.
Generate Lookalike Results:

Create a CSV file mapping CustomerID to their top 3 lookalike customers with similarity scores.
Let's start by preparing the features for similarity calculation.

The customer features have been successfully prepared with the following:

Total Spend: Total revenue contributed by each customer.
Average Transaction Value: Mean value of their transactions.
Total Transactions: Count of transactions.
Preferred Category: One-hot encoded product category for each customer.

Task 3: Customer Segmentation

Merge customer and transaction datasets.
Perform feature engineering (e.g., average transaction value, frequency of purchase).
Apply clustering algorithms (e.g., KMeans).
Evaluate clusters using DB Index.
Visualize clusters with relevant plots.
![image](https://github.com/user-attachments/assets/87d1ae84-d963-494a-9bb4-e0566a0f8d20)

Next, I’ll perform clustering on customer data to identify distinct segments. The steps include:

Feature preparation for clustering (combine customer and transaction data).
Applying a clustering algorithm (e.g., KMeans).
Evaluating clusters with the DB Index and visualizing the results.
