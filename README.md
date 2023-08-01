# Diwali Sales Analysis with Power BI
Deep dive analysis of the Diwali sales data to help the client gain more insights about their target market and improve customer experience

Diwali, also known as the Festival of Lights is one of the biggest festivals in India symbolizing the triumph of good over evil and light over darkness. The festival is celebrated for three days with main day falling on Oct 24 this year.

It is also one of the country’s largest shopping events, with consumers spending big on decorations, clothing, jewelry, gifts, sweets, lights, and fireworks.

The Objective of this project is to analyze the festive sales spending to gain insights about the target market and identify patterns to improve customer experience.
## Data exploration of the dataset using SQL
### Problem Statement:

The ecommerce store in India that we are working with has been facing difficulties in analyzing its sales trend and making data-based decisions. This limits the business's ability to seize growth opportunities and achieve its revenue targets. To address these challenges, the business needs a solution that can provide a detailed and insightful analysis of the sales trend, especially during the peak season of Diwali. 
By leveraging the sales data, the solution can help the business identify patterns, anticipate customer needs, optimize inventory allocation, and tailor marketing strategies accordingly. This will enable the business to make strategic decisions and take proactive actions to boost revenue and enhance performance.

### Analysis:
### Data Import and Initial Analysis
The sales data was provided in a CSV file, which was imported into Power BI. Initial insights were drawn from the data using visualization and analysis techniques to gain a preliminary understanding of the sales trend.
### Data Modeling
Data modeling was performed within Power BI to create relationships between the relevant tables in the Power BI. This step ensured that the data could be properly analyzed and visualized.
### Data Cleaning and Transformation
Power BI's data transformation features, such as Power Query, were utilized to clean and transform the data. Irrelevant entries, duplicates, and inconsistencies were removed or resolved, ensuring the data was accurate and reliable.

The initial analysis will help us identify the areas where we need more data granularity and how we can leverage the existing data. In this case, relevant measures and calculated columns created from this data facilitate data visualization and exploration. This will enable us to comprehend the intricacies and perform a thorough investigation of the data.
### Data Exploration and Visualization
The data is used to analyze:

•	sales, orders, number of customers by state, gender and date

•	finding the high performance categories and the respective products for each day by gender and state

•	performance of each category

•	most profitable products and their categories

•	finding the high-value customers and their preferences

•	target age group and their interests

### Measured Created:
•	Previous Day Sales

•	Nest Day Sales

•	Sales Contribution %

•	Total Orders

•	Total Sales

•	Number of Customers

### Parameters Created:

•	Sales

•	Orders

•	No. of Customers

A calculated calendar table was created for the sale days for better clarity and accurate visualization.

### Conclusion

•	Uttar Pradesh, Karnataka, Delhi, Maharashtra are the top contributors with highest revenue, order list and maximum number of customers

•	Most Consumers are Female and not married. This helps the company in creating a marketing plan targeting the specific customers.

•	Food, footwear and Furniture are the most profitable segments and have a long order list. Increasing inventory in these categories might help the client in preparing for the next big sale.

•	More than half of the top 50 high-value customers are from the state Andhra Pradesh, with Auto being their favorite category.

•	Food, Electronics and Clothing has highest number of product portfolio, with more than 800 unique products under each category.

### About the database:

This dataset is available on kaggle.

Follow the link for the dataset https://www.kaggle.com/datasets
 
Below columns are used in this dataset to obtain the mentioned conclusion.

`User_ID`    `Cust_name`	   `Product_ID`	  `Gender`     `Age Group`	    `Age`    `Marital_Status`	    `State`	   `Zone`	   `Occupation`	`Product_Category`	  `Orders`	    `Amount`
