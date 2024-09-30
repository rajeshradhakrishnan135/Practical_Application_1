## Practical Application 1: Will the Customer Accept the Coupon?
By Rajesh Radhakrishnan
Date: 09/30/2024

# URL of Jupyter Notebook that contains the Analysis


# Overview
The coupons dataset contains survey data of different drivers who are sent coupons to Bars, Coffee Houses, Restaurants 
(cheap and expensive) and Take-Away. The driver/customer is then recorded as accepting the coupon (right away or later 
before the coupon expires – both labeled Y=1) or rejecting it (Y = 0).

The goal of this analysis is to differentiate between the drivers/customers who accepted the coupon versus the ones who 
rejected the coupon – what are some of the characteristics of these two groups of customers based on the acceptance rate 
of the coupon. Two coupon types were analyzed in this report – Bar coupons and Coffee House coupons. 

# Findings
The analysis of the coupons dataset was performed to determine the characteristics of customers who accept the Bar coupons 
and Coffee House coupons.

(a) Bar Coupons: The overall proportion of bar coupons that were accepted = 0.4119. The customers/drivers who visited bars 1 
or more times a month are seen to have a higher bar coupon acceptance rate (0.6853). The majority of customers who rejected 
the Bar coupons never visited Bars. In addition, if age of the customer is considered, those with age greater than 25 years 
have a significantly higher acceptance rate than others (0.6898 vs 0.3377). The acceptance rate is lower for those with incomes 
less than 50K and who go to cheaper restaurants 4 or more times a month (0.4565). Thus, customers who accept Bar coupons are 
those with higher frequency visits to the bars whereas customer who decline the coupons are those that are less frequent to 
Bars or have lower incomes. Single customers are more inclined to accept Bar Coupons whereas those Married or having a Partner 
are more likely to reject the Bar coupons. Unemployed customers have the highest propensity to reject Bar Coupons. Students 
are more likely to accept them. Customers who accept Bar coupons typically do so when the weather is Sunny.

(b) Coffee House Coupons: The overall proportion of Coffee House coupons that were accepted = 0.4963. A majority of Coffee 
House coupon customers never visited Bars. The largest number of customers went to expensive restaurants (Restaurants20To50) 
less than once a month, and went to take-away as well as cheap restaurants 1 to 3 times a month. The acceptance rate for 
Coffee House coupons is higher for those who go to coffee houses once or more per month (the largest acceptance rate was 
seen for those who went 4-8 times a month). Among these customers, the acceptance rate was higher when the passengers were 
Friend(s) or Partners as compared to driving Alone or with Kid(s). A larger proportion of Female drivers/customers (compared 
to Male counterparts) who accepted the Coffee House coupon visited the coffee houses 1 to 3 times a month, as well as 4 to 8 
times a month. Also, the coffee house coupon customers had the highest acceptance rate when they were not headed to their 
Home or Work destination. The largest acceptance rate of coffee house coupons was when they were sent out at 10AM, whereas 
the largest number of Coffee House coupons were sent out at 6PM.

# Recommendations
One recommendation for future coupon promotions for a type of location is that it can be targeted towards the customers/drivers 
who go to the location more often. The customers who never go the location have a low acceptance rate for both Bar and Coffee 
House coupons. They can be enticed to try out a Bar or Coffee House with a free coupon or promotion and if they do, they become 
more likely to accept future coupons. Another recommendation is to avoid sending the Coffee House coupons during morning and evening 
commute hours since the customers are more likely to accept the coupon when they are headed to a non-urgent destination (targeting 
them on weekdays or weekends at 10AM can be considered).
