Customer Revenue, Risk & Retention Analytics

Project Overview:
This project analyzes e-commerce customer behavior, revenue patterns, product returns, and delivery performance using Python and Pandas.
The goal is to identify high-value customers, understand return risks, and evaluate delivery performance to generate business insights that support customer retention and revenue growth.

Tools & Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

Dataset
The project uses three datasets:
* **customers.csv** – Customer demographic and signup information
* **orders.csv** – Order lifecycle, delivery, and payment details
* **order_items.csv** – Item-level purchase information

Feature Engineering:
Several analytical columns were created to support business analysis:
* **order_value** – Calculated using quantity × price
* **delivery_delay_days** – Difference between delivery date and order date
* **is_repeat_customer** – Identifies repeat customers
* **is_high_value_order** – Flags orders above a certain value
* **customer_value_segment** – High / Medium / Low based on customer spending
* **customer_risk_category** – Customer risk classification based on return rate
* **order_reliability_score** – Score based on delivery status

Programming Logic
The project includes:
* Custom Python functions for feature creation
* Lambda expressions for logical column creation
* For-loops for specific analytical tasks
* Proper handling of missing values without blindly dropping data

Business Questions Answered
* Which customers generate high revenue but also have high return rates?
* Which cities experience the most delivery delays and revenue loss?
* Are repeat customers more valuable to the business?
* Which product categories lose revenue due to returns?
* Which payment method carries the highest risk?

Data Visualizations:
The following visualizations were created:
* Monthly revenue trend (Line Chart)
* Customer value segmentation (Bar Chart)
* Return rate by category (Bar Chart)
* Delivery delay vs revenue (Scatter Plot)
* City vs category revenue (Heatmap)

Outcome
The analysis helped identify customer value segments, revenue risks, delivery performance issues, and patterns in product returns, enabling better business decision-making for e-commerce operations.
