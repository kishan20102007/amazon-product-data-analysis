# Amazon Product Data Cleaning & Analysis

##  Project Overview

This project focuses on cleaning, transforming, and analyzing a real-world Amazon product dataset using Python, Pandas, NumPy, and exploratory data analysis techniques.

The dataset contains product information such as ratings, reviews, prices, purchases, seller badges, sponsorship status, coupons, delivery information, and collection timestamps.

##  Objectives

* Understand the structure and quality of a real-world dataset
* Identify and handle missing values
* Clean inconsistent text and numerical data
* Convert columns into appropriate data types
* Create useful features from existing data
* Analyze relationships between product attributes
* Perform exploratory data analysis
* Prepare the dataset for future machine learning work

##  Technologies Used

* Python
* NumPy
* Pandas
* Google Collabe Notebook

##  Data Cleaning

The project includes:

* Rating extraction and numeric conversion
* Review-count cleaning
* Conversion of `K+` purchase values into numerical values
* Price cleaning and conversion
* Best-seller status conversion
* Sponsored-product classification
* Coupon status processing
* Date/time conversion
* Missing-value analysis
* Duplicate detection
* Data validation

## 📊 Analysis

The cleaned dataset was used to investigate:

* Product rating distributions
* Product price distributions
* Best Seller vs non-Best Seller products
* Sponsored vs organic products
* Coupon vs non-coupon products
* Review counts
* Discount percentages
* Product popularity

##  Project Structure

```text
amazon-product-data-analysis/
│
├── data/
│   └── amazon_sales_data_cleaned.csv
│
├── notebooks/
│   └── amazon_data_cleaning.ipynb
│
├── README.md
└── 
```

##  What I Learned

This project helped me move from following Pandas tutorials to working with a messy real-world dataset. I practiced data inspection, cleaning, missing-value analysis, filtering, sorting, grouping, feature creation, and data validation.

##  Next Step

The next stage is to perform deeper EDA and then work with a machine-learning dataset that has a clearly defined prediction target.
