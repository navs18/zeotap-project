
# eCommerce Data Science Assignment

## Overview
This repository contains the solutions for an eCommerce data science assignment, focusing on Exploratory Data Analysis (EDA), Lookalike Model, and Customer Segmentation/Clustering based on a provided eCommerce transactions dataset. The dataset consists of three CSV files: `Customers.csv`, `Products.csv`, and `Transactions.csv`.

## Tasks
### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Objective:** Perform an EDA on the dataset and derive actionable business insights.
- **Deliverables:** A Python script (Jupyter Notebook) containing the EDA code and a PDF report with 5 business insights.
- **Key Insights:**
  1. Customer signup trends and regional distribution.
  2. Product category distribution and popular product categories.
  3. Transaction volume over time and its correlation to promotional activities.
  4. Revenue analysis based on transactions and customer engagement.
  5. Region-wise customer engagement and differences in transaction patterns.

### Task 2: Lookalike Model
- **Objective:** Build a lookalike model to recommend similar customers based on their profile and transaction history.
- **Deliverables:** A Python script (Jupyter Notebook) and a `Lookalike.csv` file containing the top 3 similar customers for each of the first 20 customers.
- **Methodology:** 
  - Use customer and product data to create a profile for each customer.
  - Compute similarity scores between customers using cosine similarity.
  - Recommend top 3 similar customers for each user.

### Task 3: Customer Segmentation / Clustering
- **Objective:** Perform customer segmentation using clustering techniques.
- **Deliverables:** A Python script (Jupyter Notebook) containing clustering code and a PDF report on the clustering results.
- **Methodology:** 
  - Use both customer profile information and transaction data to segment customers.
  - Perform clustering using KMeans algorithm and evaluate results using the Davies-Bouldin Index and Silhouette Score.
  - Visualize the clusters using PCA (Principal Component Analysis).

## File Structure
The repository contains the following files:

- `Customers.csv`: Contains customer profile information including ID, name, region, and signup date.
- `Products.csv`: Contains product information including ID, name, category, and price.
- `Transactions.csv`: Contains transaction data including transaction ID, customer ID, product ID, quantity, and total value.
- `FirstName_LastName_EDA.ipynb`: Python script containing EDA code.
- `FirstName_LastName_EDA.pdf`: PDF report with business insights derived from the EDA.
- `FirstName_LastName_Lookalike.csv`: CSV file containing lookalike recommendations and similarity scores.
- `FirstName_LastName_Lookalike.ipynb`: Python script for building the lookalike model.
- `FirstName_LastName_Clustering.ipynb`: Python script for performing customer segmentation using clustering techniques.
- `FirstName_LastName_Clustering.pdf`: PDF report on the customer segmentation results.

## Setup and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/eCommerce-Data-Science-Assignment.git
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   - Libraries used: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `fpdf`, etc.

3. Run the Jupyter notebooks for each task:
   - `FirstName_LastName_EDA.ipynb` for Task 1.
   - `FirstName_LastName_Lookalike.ipynb` for Task 2.
   - `FirstName_LastName_Clustering.ipynb` for Task 3.
