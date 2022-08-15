# Market-Analysis-Report-PBI

This case study is the requirement to graduate from the Udacity Nanodegree Program. 
Reference to case study in the Udacity ND program : [Data Analysis and Visualization with Power BI](https://learn.udacity.com/nanodegrees/nd331/parts/cd0014/lessons/4bc2c6c7-26bf-48b6-be2e-3a7e582e373a/concepts/7a2a8b0a-4df3-4d64-853f-c47e80bc6236)

## I. Overview 

### Project Description
An online national clothing chain needs your help creating a targeted marketing campaign. Sales have been flat and they want to lure lost customers back. They want to advertise specific products to specific customers in specific locations, but they don’t know who to target. They have three products in mind:
Shirt: $25
Sweater: $100
Leather Bag: $1,000
They need you to conduct an analysis to determine the best product to advertise to each customer.


## II. Findings  Summary

According to the requirements overview where company wants to advertise specific products to specific customers in specific locations, below are some of the insights gathered and can be used to decide to go further with the marketing campaign. As being informed, there are 3 products that company had in mind: Shirt, Leather Bag and Sweater Dress. 

1.	The correlation between income and sales shows that there is a strong positive correlation with R-square value of 0.88. 
2.	The linear regression formula to predict customer income is y = 72.43x + 72638.21 
3.	The opposite shows by the correlation between customer ratings and prod return rate, where the correlation between them shows a strong negative correlation with R-square value of – 0.83.
4.	Customer that has the highest predicted income is Jon Little with customer ID: JLit30836. His predicted income reached $1.1M
5.	The products which will be advertised the most depends on subjective assumptions and will be explained as below: 

-	According to the data provided, the product inventory table can give input regarding the number of stocks available and the product price. From these 2 parameters, we could assume that number of stocks can explain that the priority of products to be sold. The higher the stock the higher the priority because stock will impact the cash flow in both ways. Inability to sell the stock (dead-stock) will create burden to the cash flow. In this case, we categorized the priority into 3: High priority, Medium Priority and Less Priority. 
-	The product price in this case is also categorized into 3 classes: High Price, Medium Price and Low Price. We could assume that the higher the price, the higher the profit that can come into the company.  
-	Correlation on point 3 above also have impact in determining the product to be advertised. We recommend that the customer rating more than 3.5 is prioritized to be advertised. 
-	Judging from these considerations. We come up with 3 products that needs to be advertised: 
**Leather Bag**, **Long Dress** and **Wool Scarf** respectively represent High class income, medium and low. Only Leather bag is aligned with the product that company considered in the overview. However, we could prioritize the **Long Dress ** above the Leather Bag and Wool Scarf as Long Dress has better rating and lower return rate. 

### Further Analysis on the Location and Target for advertising
After the product is considered, next we tried to specify the location and segment the potential customer. External source is taken from the Bureau of Labor Statistic (bls.gov) to retrieve the data about women earnings in each state of the US. Women earning data is taken with the assumptions that long dress and sweater dress are usually being bought by women. In Target page report, we only specialized for the product that we want to advertised, divided by the income class. The income class are divided based on the predicted income from previous insights and the income by state table data given. The class is categorized to High Income, Middle Income and Low Income. 

The new customer target table can explain the percentage of class income with assumption that High Price item, in this case Leather bag, will be advertised to High Class Income people. Medium price item, - Long dress, is for medium class income people, and wool scarf is for low class income people. 
Another consideration is based on the industry worker. Based on general knowledge, clothing business is categorized within the retail trade industry. Hence, the number of retail workers is put to the table with the assumptions that the higher the number of retail workers in a state, the more the retail business operates in that state which explain the bigger the market. 

In this sense, the best strategy to target new customer is with the combination of highest women earning state, the highest number retail workers in a state, and the highest percentage of the targeted income class. 

Current customer table is also provided for the company to increase the potential of returning/recurrence customer. For sure we should advertise to our current customers. In this table, the customers are also segmented by the class income. 

Unfortunately, the data provided still has many limitations. With further collection of data, the marketing campaigns can be more specific. 

Please see the report here : [National Clothing Chain](https://app.powerbi.com/view?r=eyJrIjoiYzUzYzA3YmYtMWJjZS00OGZlLWFjNjQtN2U3OTZjZjRkNzA4IiwidCI6IjFhNGNiYmNlLWE5ZmItNGQyYS05MTU3LTBlMzlhNWNhMjc1MSIsImMiOjh9&pageName=ReportSection65ea62a00b081a59614d)
Note: The decomposition tree is not working due to limitation with the LIVE Connection. AI Splits are currently unsupported (as of August 15, 2022)
