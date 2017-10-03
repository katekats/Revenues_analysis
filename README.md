# Revenues_analysis

# Customer.csv
The customer.csv dataset contains 4 fields:
a) date
b) revenues (numeric)
c) group (chr)
d) customer_id (int)
Each customer generates (or doesn’t) revenues on a given day; moreover, each customer is assigned to a group “a” or “b”.

# Revenues_python

Using Pandas and:
1. Calculate the count of customers over time. Examine the plot for this time series.
2. Calculate the sum of revenues for each group, over time, visualize the results.
3. Create a dummy variable for each customer, with a value of 1 if revenues > 0, 0 otherwise. Calculate the percentage of customers that turn into buyers, over the total
