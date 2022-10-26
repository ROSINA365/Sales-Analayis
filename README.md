<h3>Sales-Analysis</h3>
We analyze and respond to business inquiries concerning sales data from the last 12 months using <b>Python Pandas and Python Matplotlib</b>. Numerous tens of thousands of electronics store purchases are included in the data, which is split down by month, product kind, price, purchase location, etc.

First, we clean up the information. Among the tasks in this area are: 
- Remove NaN values from the DataFrame
- Removing rows in accordance with a criteria
- Converting columns to another type (to numeric, to datetime, astype)

Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisements to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product is sold the most? Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using the split() method
- Using groupby to perform aggregate analysis
- Plotting bar graphs and lines graphs to visualize our results
- Labeling our graphs
- using the datetime library (dt.hour , dt.minute ) to add a new column for hours and minutes

