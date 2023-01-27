# Credit-Card-Clustering
Credit Card Clustering
Credit card clustering is the task of grouping credit card holders based on their buying habits, credit limits, and many other financial factors.  It is also known as credit card segmentation. Such clustering analysis helps businesses find their potential customers and many more marketing strategies.
Initially Importin necessary libraries like Numpy, Pandas, Sklearn etc and loading the Dataset.
There are three features in the dataset which are very valuable for the task of credit card segmentation:

    BALANCE: The balance left in the accounts of credit card customers.
    PURCHASES: Amount of purchases made from the accounts of credit card customers.
    CREDIT_LIMIT: The limit of the credit card.
I have added a new column as “CREDIT_CARD_SEGMENTS”. It contains labels about the group of credit card customers. The groups formed range from 0 to 4. For simplicity, I will transform the names of these clusters:
Visualize the credit card clusters we found from our cluster analysis.
