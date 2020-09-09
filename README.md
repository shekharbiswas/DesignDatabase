# DesignDatabase

This project create a sample database out of E-commerce data.

* **product_output.jsonl** contains the product informations and **search_output.jsonl** contains the basic summary of products.
* **create_df.ipynb** creates dataframe out of the above mentioend json files. **s.csv** is the summary dataframe.
* **create_database.ipynb** save the dataframes in SQL tables with help of SQLAlchemy.
* **reviews.py** extract all the recent reviews from Amazon products. It takes **urls.txt** and **selectors.yml** as inputs and output the resuls on **data.csv**.

