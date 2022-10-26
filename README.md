# Problem Statement:
A bike sharing company has recently faced a significant dip in its revenue and we would like to understand why. Especially as data scientists, determine the factors which are good predictors of demand with a certain level of confidence. Further on the basis of these strong predictors of demand we also need to give recommendations to the company.


# Insights :
- Clear, working winter day is the most common day reported in the data
- The count of casual, registered and total rental bikes per hour shows a somewhat poisson distribution
- Temp, feeling temp, humidity and windspeed are also somewhat normally distributed centered around 20, 25, 60 and 13 respectively


- Insights from visual EDA : 
    - Most bikes seems to be rented in fall and the least in spring
    - There seems to be slightly more number of bikes rented on a holiday as compared to no holiday (very small difference)
    - There seems to be slightly lesser number of bikes rented on a working day (very small difference)
    - Most bikes are rented on clear days and the least on rainy days


- We cannot infer that working day has an effect on number of bikes rented (t-test pvalue is 22.6%)


- We can infer that weather has a significant effect on number of bikes rented (f-test pvalue is ~0%)
- We can infer that clear weather is linked to increase in number of bikes rented (Welch t-test pvalue ~0%)


- We can infer that season has a significant effect on number of bikes rented (f-test pvalue is ~0%)
- We can infer that summer and fall season is linked to increase in number of bikes rented (Welch t-test pvalue ~0%)


- We can infer that season has a significant effect on the weather (chisquare-test pvalue is ~0%)

# Recommendations : 

- The bike sharing company should start extensive marketing campaigns at the start of summer season and run them all the way through fall season.
- During these 2 seasons they should increase their supply of cycles, and install more pick up/drop locations to make sure that the demand is fully met.
- They should also introduce Miles Points (like flights) during these seasons to build customer loyalty and retain them for the next year as well.