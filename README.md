# Credit-Card-Customer-Segmentation

A customer segmentation analysis project using Python, applying the K-Means algorithm to credit card usage data.

## Project Overview

The goal of this project was to perform a customer segmentation analysis on a credit card dataset to identify distinct customer groups. By understanding these segments, a company can develop tailored marketing strategies, improve customer retention, and optimize product offerings.

## Methodology

The analysis followed a standard data science pipeline:

1.  **Data Preprocessing**: The dataset was cleaned using **Python**'s `pandas` and `scikit-learn` libraries. Missing values were handled, and features were scaled to ensure they were on a comparable level for the clustering algorithm.

2.  **Clustering**: The **K-Means algorithm** was used to group customers based on their behavioral variables. The optimal number of clusters was determined to be **4** using the **Elbow Method**.

3.  **Cluster Analysis**: The average values of each feature were calculated for each cluster. This allowed for the creation of a detailed profile for each customer segment.

## Key Findings and Customer Segments

The analysis revealed four distinct customer segments with unique spending and usage habits.

* **Segment 0: High-Engagement Users**
    * This segment represents the most consistent and valuable customers. They have a healthy balance of both single-go and installment purchases and use their credit card frequently. They are an ideal target for loyalty programs and rewards.

* **Segment 1: Power Users**
    * This is the top-tier segment characterized by very high overall spending, particularly in one-go purchases. They have the highest credit limit and use their card frequently for large transactions. This group is likely to be high-income and could be targeted with exclusive, premium product offers.

* **Segment 2: Cash Advance Users**
    * This group's primary use of their credit card is for cash advances rather than making purchases. They have the highest average cash advance amount and number of cash advance transactions. Marketing efforts for this group should focus on encouraging them to use their cards for purchases rather than cash.

* **Segment 3: Low-Engagement Users**
    * This segment represents customers with low overall spending and infrequent card usage. They have low balances and make minimal payments. This group could be targeted with campaigns designed to increase card activity, such as special promotions for first-time purchases.

## Tools Used

* **Python**: `pandas`, `scikit-learn`, `matplotlib`
* **Jupyter Notebook**: For a reproducible analysis and presentation
* **GitHub**: For project documentation and version control

## Files in this Repository

* `Credit Card Data.csv`: The raw dataset used for this analysis.
* `credit_card_segmentation.ipynb`: A Jupyter Notebook containing all the code and analysis.
* `README.md`: This file, which serves as a project summary.
