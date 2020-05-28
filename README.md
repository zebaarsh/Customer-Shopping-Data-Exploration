# Customer-Shopping-Data-Exploration

**Data Description:**

The data provided for this task represents customer shopping data for a single store over a certain period of time. Each unique id represents a different customer, and every row is a separate transaction.
 


**Questions:**

1. Create a column in the dataframe that shows how much each customer spends per visit (per day).

2. Create a column that shows the number of previous visits per customer. 

3. Referencing the previous question, write a SQL query that would return the same result.

4. Create a column that shows the cumulative count (rolling sum) of previous purchases (per customer) that took place in department 99.

5. Create a histogram that shows the distinct visits per customer. A distinct visit is defined as a customer visiting the store on two separate days.

6. Plot the distribution of days between visits, per customer. For example, if a customer comes in on 1/1/2019 and again on 1/3/2019, the days between visits equals 2 days.

7. Write a function that “looks into the future” and creates a Boolean column in your dataframe. The column will have a value of 1 if the customer comes in to the store (and completes a purchase) within the next five days, 0 otherwise.

8. Plot the distribution of how much customers spend per day.

9. Which customer(s) has the highest number of consecutive shopping days?

10. On average how often do customers come in per month?

11. Plot the average dollar amount spend per month?

12. By this point you've done enough EDA to have a decent understanding of the data you are working with. Without writing any code, please explain below how you would build a useful model around this data. 
    1. What other data do you wish you could have had access to?
    2. In your opinion, what would the company holding this data care about?
    3. What would be your target variable (label)?
    4. What machine learning algorithm would you implement and why?
    5. What type of visualization would be helpful?
