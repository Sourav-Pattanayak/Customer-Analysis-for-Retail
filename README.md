# 🛒 Retail Case Study: Customer Analysis for Retail

## 📋 Project Overview

This project, provided by [Analytix Labs](https://www.analytixlabs.co.in/data-science-specialization-course/lg?utm_campaign=&utm_term=analytixlabs&utm_source=adwords&utm_medium=ppc&hsa_src=g&hsa_ver=3&hsa_cam=20774869605&hsa_kw=analytixlabs&hsa_ad=681079026671&hsa_tgt=kwd-437357826955&hsa_mt=b&hsa_acc=4064995850&hsa_grp=159598918470&hsa_net=adwords&gad_source=1&gclid=CjwKCAjwlbu2BhA3EiwA3yXyu_4SK2GILi0NH-tOdARj0N5epksa0J_oNYk6n1aATTzz2Bh0yalq1RoCt8IQAvD_BwE), focuses on analyzing customer data from a retail store to uncover actionable insights into customer behavior, sales performance, and product popularity. The analysis includes merging datasets, generating summary reports, creating visualizations, and answering key business questions that help in making data-driven decisions.

## 📂 Data Description

- **📄 Retail Data.xlsx**: The core dataset, organized into three sheets:
  1. **👥 Customer**: Demographic details of customers.
  2. **💳 Transaction**: Records of customer transactions.
  3. **📦 Product Hierarchy**: Information on products, including categories and subcategories.

## 🎯 Objectives

1. **🔗 Data Merging**: Combine the Customer, Transaction, and Product Hierarchy datasets into a single dataset (`Customer_Final`), ensuring to include only those customers who have made transactions.
   
2. **📊 Summary Report**:
   - Extract column names and corresponding data types.
   - Identify the top/bottom 10 observations.
   - Provide a five-number summary (min, Q1, median, Q3, max) for continuous variables.
   - Generate frequency tables for categorical variables.
   - Create histograms for continuous variables and bar charts for categorical variables.

3. **📈 Business Insights**:
   - **📅 Time Period**: The available transaction data spans from **January 1, 2012, to September 9, 2013**.
   - **👫 Product Popularity by Gender**:
     - **Females**: Bags, Books, Clothing, Electronics, Footwear, Home and Kitchen.
     - **Males**: Bags, Books, Clothing, Electronics, Footwear, Home and Kitchen.
   - **🏬 Store Performance**: Flagship stores earned a total of **₹8,526,843** from the Electronics and Clothing categories.
   - **🔟 High-Value Customers**: There are **6 customers** with more than 10 unique transactions.

## 🛠️ Tools Used

- **🐍 Python**: For data processing and analysis.
- **📊 Pandas**: To manage and manipulate datasets.
- **📉 Matplotlib/Seaborn**: For creating insightful visualizations.
- **📝 Jupyter Notebook**: As the interactive environment for developing and showcasing the analysis.

## 🚀 How to Run the Project

1. Clone the repository or download the project files.
2. Ensure you have the necessary Python libraries installed:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
3. Open and run the Jupyter Notebook (`1.Retail Case Study.ipynb`) to explore the analysis.

## 🔍 Key Insights

- **Top Performing Categories**: Electronics and Clothing emerged as top-grossing categories, with Electronics being particularly popular among male customers.
- **Customer Demographics**: The majority of customers hail from a specific city, indicating potential for targeted marketing in that area.
- **Store Performance**: Flagship stores lead in revenue generation, especially in the Electronics category.

These insights are crucial for tailoring marketing strategies, optimizing product placements, and enhancing customer engagement to drive sales.

---

Feel free to explore the analysis and discover how data can be transformed into actionable business intelligence! 🚀
