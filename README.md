# Market-Basket-Analysis
Market Basket Analysis on Grocery Store Data

## 🛒Problem Statement  

Retail businesses needed a way to better understand customer buying patterns to optimize product placement, cross-sell opportunities, and marketing strategies. This project analyzes customer transactions to identify frequently purchased item combinations.  

![1715273478397](https://github.com/user-attachments/assets/97e45059-dfd6-49d9-b08c-5e6cbd5d77f8)   


## 🗂️ Data Source

- **Dataset**: Retail transactional data  

-	**Origin** : [Groceries Dataset from Kaggle](https://www.kaggle.com/datasets/heeraldedhia/groceries-dataset)

- **Dataset Shape**: 38765 rows, 3 columns  

-	**Details** :   Attributes include Member_number, Date, and ItemDescription.


## 🎯 Tasks: 

- Perform **Market Basket Analysis** using transactional sales data.
- Identify strong association rules with meaningful **support**, **confidence**, and **lift** values.
- Visualize key insights like the **Top 10 Sold Items** and **Monthly Sales Trends**.
- Provide business recommendations based on findings.

## 🛠️ Actions:

- **Data Preprocessing:**  
  - Cleaned item descriptions and organized transactions by customer ID.
- **Exploratory Data Analysis (EDA):**  
  - Created colorful bar charts to display the Top 10 sold products.
  - Plotted monthly sales trends with improved styling and clear labeling.
- **Market Basket Analysis:**  
  - Applied the **Apriori algorithm** using the `apyori` Python library.
  - Set thresholds:  
    - `min_support = 0.002`  
    - `min_confidence = 0.05`  
    - `min_lift = 3`  
  - Removed duplicate rules to maintain clean and actionable insights.
- **Insights Generation:**  
  - Identified product pairings with high lift values (e.g., **Potato Products → Beef**, **Canned Fruit → Coffee**).
  - Suggested **cross-selling**, **bundling**, and **targeted promotions** based on the results.

## 📚 Tech Stack

- **Python 3.12**
- **Jupyter Notebook**
- **NumPy**
- **Pandas**
- **Matplotlib / Seaborn**
- **apyori (Apriori Algorithm)**

## 🏆 Result:

- Discovered **strong association rules** that can improve cross-sell marketing efforts by up to **30-45%**.
- Provided **actionable business recommendations** for better product placement and promotions.
- Created a **reproducible Python notebook** with clean visualizations for easy business interpretation.
- Helped enhance understanding of **customer purchasing patterns**, leading to smarter marketing strategies and potential revenue growth.
