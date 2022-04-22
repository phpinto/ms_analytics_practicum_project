# Product Name Match and Item Relationship Exploration on Transaction Logs

Repository for the MS Analytics Practicum Project for CSE/ISYE/MGMT 6748 Fall '20. This project was completed along with Hannah Hamilton, Qihang Zhang, Jingyu Li and Xinze Wang.

### 1. Data
- All dataset should be put in "/jupyter_notebooks/raw_data/".
- Dataset "/jupyter_notebooks/raw_data/third_party/food.csv": grocery product list by USDA (https://www.usda.gov/content/usda-open-data-catalog)
- Dataset "/jupyter_notebooks/raw_data/third_party/generic_food.csv": grocery product list by Instacart.
- Dataset "/jupyter_notebooks/raw_data/third_party/instacart/\*": more product information datasets by Instacart.
- Dataset "/jupyter_notebooks/raw_data/third_party/grocery.com/\*": files from the Open Grocery Database Project by grocery.com.
- Model Outputs "/jupyter_notebooks/raw_data/model_outputs/\*": this folder contains some files output by our models.


### 2. Problem 1 setup: Product name match
- **Step1:** run notebook "/jupyter_notebooks/problem1_name_match/master_catalog_generation.ipynb"
- **Step2:** run notebook "/jupyter_notebooks/problem1_name_match/similarity_based_approach.ipynb.ipynb"

### 3. Problem 2 setup: Item recommendation
- **Apriori algorithm for complementary products:** run notebook "/jupyter_notebooks/problem2_product_recommendation/apriori_optimized_min_support_of_top_10%_cleaned_v2.ipynb" and "/jupyter_notebooks/problem2_product_recommendation/apriori_optimized_small_transactions_min_support_of_top_10%_cleaned_v2.ipynb".
- **Transaction context co-occurrence for substitute products:** run notebook "/jupyter_notebooks/problem2_product_recommendation/substitute_exploration_transaction_context.ipynb".
- **Graph-based GCN for substitute products:** run notebook "/jupyter_notebooks/problem2_name_match/graph_based_item_recommendation.ipynb"

