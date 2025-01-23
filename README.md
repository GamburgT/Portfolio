# Portfolio
## 1. Customer Database Analytics
**Overview**
This notebook contains an analysis of an open-source dataset related to customer shopping trends. The dataset is used to explore various customer behaviors and preferences without disclosing any personal data. The analysis focuses on understanding customer demographics, subscription status, purchase patterns, and other factors that could influence business strategies to increase revenue.

**Libraries Used**<br/>
Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib: For creating static, animated, and interactive visualizations.

Seaborn: For making attractive and informative statistical graphics.

**Dataset**<br/>
The dataset used in this analysis is named shopping_trends.csv. It includes various attributes related to customer purchases such as:

* Size
* Category
* Season
* Subscription Status
* Payment Method
* Shipping Type
* Discount Applied
* Promo Code Used
* Preferred Payment Method
* Frequency of Purchases

**Data Cleaning and Initial Analysis**<br/>
Data Inspection: The dataset was checked for null values and duplicates. It was found to be clean with no null values or duplicates.

Data Types: The dataset contains a mix of categorical and numerical data types.

**Key Insights**<br/>
*Subscription Status*<br/>
Majority is not Subscribed: A significant portion of customers are not subscribed, which may limit their access to updated stock information.

Correlation with Gender and Discounts: Subscription status is correlated with gender, applied discounts, and promo code usage. Male customers are more likely to be subscribed and use discounts.

*Customer Demographics*<br/>
Gender Distribution: The dataset shows a gender imbalance, with more male customers than female.

Age Distribution: Female customers tend to be younger than male customers.

*Purchase Behavior*<br/>
Discount Usage: Male customers are more likely to apply discounts compared to female customers.

Clothing Size: The majority of purchases are for medium-sized clothing, indicating a potential need to stock more of this size.

*Category and Frequency*<br/>
Preferred Categories: Subscribed customers prefer clothing and accessories, aligning with the overall category distribution.

Purchase Frequency: There is no strong preference in purchase frequency or payment method across the dataset.

**Visualizations**
* Pie Charts: Used to show the distribution of subscription status and gender.
* Bar Plots: Used to compare subscription status and discount application by gender.
* Heatmaps: Used to visualize the correlation between various factors and subscription status.
* Count Plots: Used to display the frequency of purchases, preferred payment methods, and seasonal purchase trends.

**Suggestions for Business Strategy**
* Promo Campaigns: Launch promotional campaigns targeting female customers to increase subscriptions and discount usage.
* Stock Management: Ensure adequate stock of medium-sized clothing and assess the availability of other sizes to meet customer demand.
* Marketing Strategies: Develop marketing strategies to retain subscribed customers by focusing on popular categories and sizes.

**Conclusion**<br/>
The analysis highlights the need for targeted marketing efforts to address the gender imbalance and increase subscription rates. By leveraging promo codes and discounts, the business can attract more female customers and enhance overall customer loyalty. Additionally, maintaining optimal stock levels for popular sizes and categories will help in meeting customer expectations and driving sales.

**How to Run the Code**<br/>
Ensure you have the required libraries installed. You can install them using pip:

!pip install pandas numpy matplotlib seaborn<br/>
Download the dataset shopping_trends.csv and place it in the same directory as the notebook.

Open the notebook in Jupyter or any compatible environment and run the cells sequentially to perform the analysis and generate visualizations.

**Author**<br/>
Tatiana Gamburg
