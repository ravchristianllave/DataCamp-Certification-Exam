# About the DataCamp Data Analyst Professional Exam

DataCamp Data Analyst professional exam is a two-step certification by successfully passing a timed exam (DA201) and a practical exam (DA601P). In this project, the practical exam is presented where Python is used to solve a business case. You can see more information in here: *https://support.datacamp.com/hc/en-us/articles/7635051866903-Data-Analyst#h_01HEBHV1R9GJ8JDJ279MA04VAB*



# Business Case

Pens and Printers is a company that sells high quality office products to large organization. They are launching a new product line but they have to make sure they will be using a sales tactic effectively. The following sales strategies are assessed:

- **Email**
- **Call**
- **Email and Call**

To analyze these strategies methods, **Python** is used to perform an exploratory data analysis. The head of analytics asked to answer the following questions:

- How many customers were there for each approach?
- What does the spread of the revenue over time for each method?
- Was there any difference in revenue over time for each methods?
- Based on the data, which method would you recommend we continue to use? Some of these methods take more time from the team so they may not be the best for us if the results are similar.

To give you an overview of the analytical process using Python:

1. **Data Importing and Validation** - the table is imported in Jupyter notebook and validated the shape, info, count of sales strategies, defining a function and cleaning methods. See the information of the product_sales table in the attached picture.
2. **Exploratory Analysis** - business metrics were analyzed using Pandas, Numpy and Seaborn to determine which sales strategy is the most effective.



# product_sales Table

![undefined](https://cdn.mavenanalytics.io/public/profile/a891b370-5021-704e-8440-4d3d6fbf7625/projects/Capture123.JPG)

# Key Insights

After acquiring some metrics for each sales method, the insights gained are the following:

- While 'Email' has the highest ARCPSE, the 'Email + Call' method generates more customer engagement, as evidenced by higher website visits and average items purchased. This could lead to stronger customer relationships and long-term growth.
- The 'Email + Call' method has shown a consistent upward trend in revenue generation over six weeks, indicating its potential for continued success.
- The 'Call' method is the least efficient in terms of effort and revenue generation and has a downward trend in revenue over time. In conclusion, the 'Email + Call' method should be prioritized for sales efforts, as it demonstrates better customer engagement, consistent revenue growth, and a more sustainable balance between effort and return.
