# MS-Excel-project-ABC-Bank-Report

The source of my sample dataset is kaggle.com and the data is related to the credit card transactions belonging to multiple people for a period of January 2023 to October 2023. 
Below is the link to access the dataset:
https://www.kaggle.com/datasets/rajatsurana979/comprehensive-credit-card-transactions-dataset

For my analysis, I am assuming that this data belongs to ABC Bank which wants to create a credit card transactions report based on customer data from Jan 2023 to Oct 2023, 
to understand their customer's spending trend to come up with promotions and offers to retain existing customers and attract new customers in the upcoming financial year.

The sample questions used for my analysis are as follows:
1.	Which month has the greatest number of transactions?
2.	Which gender has the greatest number of transactions recorded?
3.	Relation between customer’s age and gender based on number of transactions.
4.	Which category is contributing towards maximum transactions?
5.	List the top 10 customers based on number of transactions.
6.	Relation between customer’s gender and the sales categories based on number of transactions.
   
Before analyzing the data, I undertook data cleaning (ensured there are non-null values and checked that the Transaction Amount and Age columns have numerical non-null values) 
and data processing (needed to add columns for Transaction Month and Age Group as well as write appropriate Excel formulas to retrieve the values in these additional columns.)

Using the Pivot (Table & Chart) along with Slicer feature in MS Excel, I could analyze the transactions data from various perspectives in the dashboard and derive the following insights:
1.	Considering that ~10% of the customers have not disclosed their gender, we observe that female customers (~46%) spend slightly more than male customers (~44%).
2.	The Travel category has the greatest number of transactions (~58%).
3.	When we compare the customer’s gender with the sales categories, we observe that the Travel category (which has the greatest number of transactions) have majority female customers (~27%).
4.	Even the top 10 customers show a trend of spending the most in the Travel category.
5.	When we compare the customer’s age and gender, we observe that majority of the customers are female from the Senior age group (~20.70%).

As a conclusion based on the above insights, I suggest that ABC Bank should consider targeting mainly the female customers especially from Senior (50 years and above) age group 
by coming up with promotions and offers in collaboration with some of the top merchants in the Travel category.
