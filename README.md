# Cohort-Analysis-Order-Rate-in-Python
Cohort analysis to determine how many days pass before a customer orders after a customers signup date.

## Introduction:
A cohort analysis takes cohorts, or groups such as a group of customers, and tracks their common behaviors or patterns over time. For example, a cohort could be a group of customers/users for a particular week or month when that customer/user signed up. By grouping customers into cohorts, one can track retention rate of a product or app, engagement of a new UI change, or percentage of active users.

There are 3 types of cohort:

- Time Cohorts: looks at customers who signed up during a particular time.
- Behavior Cohorts: looks at customers based on behaviors/actions over a certain time period, e.g. grouping them based on the type of product or service they have purchased.
- Size Cohorts: looks at various sizes of customers who purchase, subscribe, or use something.

## Objective of this project
Group the customers into week long (7 days) cohorts and then calculate how many distinct customers ordered within X days from their signup date.

1. You can run the script by simply starting at the top and running each chunk of code as long as the correct files are uploaded and the name is correct.
2. The script will prepare the files to be properly merged, merge them, and make cohort groups based on signup dates.
3. Some cleaning of the data will occur to get Q1 of 2015 and then the correct pivot tables will be made so that calculations can be done. 
4. A heatmap is made which shows the number of days (7 day periods) that passed for customers making their first order for cohort groups based on signup date.
5. Then a csv file is made which has some additional formatting and includes total number of orderers and first time orders for each cohort. 


#### Dependencies
- Python 3.6 or 3.7
- Pandas library
- Matplotlib library
- Seaborn library
- Numpy library

