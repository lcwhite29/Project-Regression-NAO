# Project-Regression-NAO

- This project shows the total greenhouse gas (GHG) emissions over the last 30+ years and attempts to model the total GHG emissions for the next 5 years.
- It begins by using pandas a common data analysis and data science library to read in an Excel file from an [ONS](https://www.ons.gov.uk/economy/environmentalaccounts/datasets/ukenvironmentalaccountsatmosphericemissionsgreenhousegasemissionsbyeconomicsectorandgasunitedkingdom) atmospheric emissions data source.
- Then using pandas the data is cleaned to find the most important data and put it into a usable form.
- From here we can plot the emissions for the last 30+ years.

![](Picture_16.png)

- Taking the graph of the last 30+ years into account, to try and predict the next 5 years' GHG emissions I decided to use a standard linear regression model.
- With the data frame including the year and total GHG emissions I used sklearn's linear regression model to predict the value of GHG emissions for 2022-2026.
- I then added the years and predictions to a data frame. This data frame along with the one for the last 30+ years was then used to create a graph of predictions.
- Additionally, I added the linear regression line.

![](Picture_17.png)
