# Online Retail Dataset - Customer Segmentation

![project_header](https://github.com/adzict/online_retail_customer_segmentation/blob/main/assets/target-group-large.jpg)

## Table of Contents

1. [ Project Introduction ](#Project_Introduction)
2. [ Technologies Used ](#Technologies_Used)    
3. [ Methods Used ](#Methods_Used)
4. [ Project Description ](#Project_Description)
   * [ 1. Data Sources ](#Data_Sources)
   * [ 2. File Descriptions ](#File_Descriptions) 
5. [ Feature Notebooks and Deliverables ](#Notebooks_deliverables)
6. [6. Conclusion and Future Recommendations](#conclusion)
7. [ Licences ](#Licences)
8. [ Contact ](#Contact)

## Project Introduction
<a name="Project_Introduction"></a>

This project is aimed at identifying customer clusters / segments based on their purchasing behaviour using K-Means Clustering.

## Technologies Used
<a name="Technologies_Used"></a>

* [Python](https://www.python.org/)
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Matplotlib](https://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)
* [NLTK](https://www.nltk.org/)
* [scikit-learn](https://scikit-learn.org/stable/)

## Methods Used
<a name="Methods_Used"></a>

* Data Processing / Data Cleaning
* Data Analysis
* Descriptive Statistics
* Feature Engineering
* Data Visualization
* Text Preprocessing
* Principal Component Analysis
* Clustering Customers using K-Means Clustering
* Evaluating Model Results
* Reporting

## Project Description
<a name="Project_Description"></a>

The success of any business depends on its ability to understand its customers and cater to their needs. With the rise of e-commerce and online shopping, it has become increasingly important for businesses to have a deep understanding of their customer base. One way to gain insights into customer behavior is through the use of clustering techniques. In this project, I aim to identify customer segments based on their purchase behavior using RFM analysis and K-Means clustering. I will also heavily focus on Feature Engineering as providing more features will yield better results.

### Data Sources
<a name="Data_Sources"></a>

This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

[Data Source](https://archive.ics.uci.edu/ml/datasets/online+retail)

**Attribute Information:**

- **InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
- **StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- **Description**: Product (item) name. Nominal.
- **Quantity**: The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
- **CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- **Country**: Country name. Nominal, the name of the country where each customer resides. 

### File Descriptions
<a name="File_Descriptions"></a>

* [Data](https://github.com/adzict/online_retail_customer_segmentation/blob/main/Online%20Retail%20Customer%20Segmentation.xlsx) - raw data
* [Assets](https://github.com/adzict/online_retail_customer_segmentation/tree/main/assets) - folder containing assets such as images
* [Online Retail Customer Segmentation.ipynb](https://github.com/adzict/online_retail_customer_segmentation/blob/main/Online%20Retail%20Customer%20Segmentation.ipynb) - Notebook containing the project

## Feature Notebooks and Deliverables
<a name="Notebooks_deliverables"></a>

### Structure of Notebooks
<details>
   <summary>Collapse</summary>

      1. Data Preprocessing and Basic EDA

            1. Imports
            2. Data
            3. Basic EDA
               3.1 Missing values
            4. Data Preprocessing
               4.1 Removing the missing values
               4.2 Checking for duplicate rows
               4.3 Outliers
            5. RFM Analysis
               5.1 Recency
               5.2 Frequency
               5.3 Monetary Value
               5.4 RFM Segmentation using scores
               5.5 Visualizing the RFM Level customers using a bar plot
            6. Clustering products into product categories
               6.1 The Elbow Method
               6.2 Visualizing the clusters
            7. Customer Segmentation using Unsupervised Learning
               7.1 PCA
               7.2 K-Means Clustering
            8. Understanding Clusters
</details> 

### 6. Conclusion and Future Recommendations
<a name="conclusion"></a>

In conclusion, this project aimed to identify customer segments based on their purchase behavior using RFM analysis and K-Means clustering. By analyzing a transnational dataset containing all the transactions of a UK-based online retail company, I was able to gain insights into the purchasing habits of their customer base. Feature engineering played a critical role in enhancing the quality of our results, as it provided us with additional variables to use in my analysis.

The results of the analysis revealed that the customer base could be divided into several distinct segments based on their purchasing behavior. By understanding these segments, the company can tailor its marketing efforts to better meet the needs of its customers, leading to increased customer loyalty and satisfaction.

Overall, this project highlights the importance of understanding customer behavior in today's e-commerce landscape and demonstrates how clustering techniques, coupled with feature engineering, can be powerful tools for gaining insights into customer behavior.

## Licenses
<a name="Licences"></a>

[Database Contents License (DbCL) v1.0](https://opendatacommons.org/licenses/dbcl/1-0/)

## Contact
<a name="Contact"></a>

Find me on [LinkedIn](https://www.linkedin.com/in/tanja-ad%C5%BEi%C4%87/), [Twitter](https://twitter.com/adzic_tanja) or [adzictanja.com](https://www.adzictanja.com/).