# rmf_analysis
Real-based information from Amazon sample
The current page contains a Jupyter notebook titled **product_amazon_customers_sellers.ipynb**, which appears to be focused on analyzing Amazon e-commerce data. Here's a summary of the key points:

- **Data Source**: The notebook references a dataset available on Google Sheets, which seems to include Amazon product reviews but lacks transactional data like invoices and dates.
- **Data Analysis**: The notebook includes Python code for data preprocessing, such as converting strings to floats, renaming columns, and handling missing values.
- **Insights Extraction**: It suggests analyzing the recency, frequency, and monetary value of product reviews to gauge product popularity and customer engagement.
- **Visualization**: There are histogram plots for the distribution of answered questions and other exploratory data analysis steps to understand the dataset better.

This summary provides an overview of the notebook's purpose and the types of analyses being conducted on the Amazon e-commerce data. As for finding new interesting Exploratory Data Analysis (EDA) insights in the Amazon marketplace DataFrame that are valuable for sellers, here are a few suggestions:

1. **Product Category Popularity**: Analyze the `amazon_category_and_sub_category` column to find out which categories and sub-categories are most popular.

2. **Manufacturer Popularity**: Analyze the `manufacturer` column to find out which manufacturers' products are most popular.

3. **Price vs. Reviews**: Analyze the relationship between `price_£` and `number_of_reviews` to see if there's a correlation between price and the number of reviews a product receives.

4. **Price vs. Rating**: Analyze the relationship between `price_£` and `average_review_rating` to see if there's a correlation between price and product rating.

5. **Product Description Word Analysis**: Analyze the words used in `product_description` to see if certain words are associated with higher ratings or more reviews.
