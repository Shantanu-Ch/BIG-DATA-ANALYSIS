# BIG DATA ANALYSIS

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : SHANTANU CHHETRI

*INTERN ID* : CT08DF2604

*DOMAIN* : DATA ANALYTICS

*DURATION* : 8 WEEKS

*MENTOR* : NEELA SANTOSH

# Large-Scale Data Analysis Using Dask
This project demonstrates scalable data analysis using Dask, a powerful parallel computing library in Python. The analysis is performed on the Instacart Market Basket Analysis dataset, which consists of millions of grocery order records from an online retailer. Dask is leveraged to process this large dataset efficiently without exhausting system memory, showcasing how it can scale from laptops to clusters.

**Project Highlights**

* Tool Used: Dask (with Pandas-like API for lazy and parallel computation)

* Platform: Jupyter Notebook

* Dataset: Instacart Market Basket Analysis (25M+ rows)

* Goal: Perform 10 insightful analytical tasks to extract patterns and trends from the dataset.

**Tasks Performed**

* Load and explore large CSV files using Dask DataFrames.

* Merge multiple datasets (orders, products, departments) efficiently.

* Find the most ordered products.

* Analyze ordering habits by day of the week and hour of the day.

* Identify the most ordered departments.

* Check reorder frequency of products.

* Analyze basket size distribution.

* Calculate average number of products per order.

* Determine top 10 users by total orders placed.

* Plot order frequency trends over time.

**Why Dask?**

Unlike Pandas, Dask allows out-of-core computation by processing data in chunks and utilizing multiple cores. This makes it ideal for handling datasets that don’t fit in memory.

**Visualization**

Matplotlib and Seaborn were used for generating visual insights, while ensuring compatibility with Dask using .compute() for triggering actual computations.

