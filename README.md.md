
# Customer Purchase Insights


## Summary
A data analytics project analyzing 3,900 customer purchase records to uncover trends in spending behavior, top-selling categories, and the impact of discounts. This project connects Python, MySQL, and Power BI to turn raw data into actionable business insights.

**Dataset Overview**
- Dataset - 
- Total Records: 3,900  
- Columns: 18  
- Key Fields: Customer_ID, Age, Gender, Item_Purchased, Category, Purchase_Amount, Discount_Applied, Review_Rating, Subscription_Status, Shipping_Type  
- Missing Values: 37 in 'Review_Rating' column (imputed with median)

## Features

- Cleaned and analyzed customer shopping data using Python (pandas).
- Integrated the dataset into MySQL for structured queries.
- Built interactive visualizations in Power BI.
- Identified top-selling products, customer segments, and discount patterns.
- Suggested actionable business recommendations to improve future sales.


## Image
![Dashboard Preview]([assets/dashboard.png](https://github.com/awasthisakshi000-code/customer_purchase_insights_python_sql_powerbi/blob/main/dashboard.png.png))

## List
- Excel (initial exploration)
- Python (Pandas, NumPy, SQLAlchemy, Jupyter Notebook)
- MySQL Workbench
- Power BI
- Git


## How it works
1. Cleaned and prepared the dataset in Python.  
2. Loaded the cleaned data into a MySQL database using SQLAlchemy.  
3. Ran SQL queries to explore purchase behavior, discounts, and product performance. ([assets/sqlqueries_customer_shopping_behavior](https://github.com/awasthisakshi000-code/customer_purchase_insights_python_sql_powerbi/blob/main/sqlqueries_customer_shopping_behavior.sql))
4. Imported SQL results into Power BI for dashboard creation. ([assets/dashboard.png](https://github.com/awasthisakshi000-code/customer_purchase_insights_python_sql_powerbi/blob/main/dashboard.png.png))
5. Delivered key insights and recommendations for future growth. 

## Insights
- Young Adults are the most active and highest-spending group.  
- Clothing and Accessories generate the highest revenue.  
- Around 27% of customers are subscribers — opportunity to expand recurring sales.  
- High-value customers prefer express shipping options.  
- Discounts increase sales volume but slightly reduce average revenue per order.

## Recommendations
1. Launch loyalty and referral programs to increase repeat purchases.  
2. Target young adult customers with seasonal marketing campaigns.  
3. Promote high-margin categories like Clothing & Accessories.  
4. Provide free express shipping for large orders to boost conversions.  
5. Use customer segmentation insights to personalize email campaigns.

## How to run the project
# Clone repository
git clone https://github.com/yourusername/customer-purchase-insights.git
cd customer-purchase-insights

# Install dependencies
pip install -r requirements.txt

# Run analysis in Jupyter
jupyter notebook

# (Optional) Load data into MySQL
python load_to_mysql.py


## Contact
👩‍💻 **Author:** Sakshi Awasthi  
📧 **Email:** awasthi.sakshi000@gmail.com 
🔗 **LinkedIn:** [linkedin.com/in/yourprofile](https://www.linkedin.com/in/sakshiawasthi000/)

## License
This project is created for learning and portfolio purposes.  
Feel free to explore, fork, and adapt it with credit.





