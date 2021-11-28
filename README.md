# Telecom-Churn-Analysis 
Performing an Exploratory Data Analysis on Telecom Company for preventing customer churn.

**Business Problem** - 
    To Explore and analyze the data provided by Orange S.A., to discover key factors responsible for customer churn and suggest ways to ensure customer retention.
    
**Business Metric** - 
    Decrease % of customer churn rate (or increase the % of customer retention).
    
**Data Provided** - 

    Target Feature :
    
      1. Churn (Bool type) Further I have converted it into int type with value 0 and 1 for False and True respectively. Note: Churn is a type of Categorical feature.
        
    Numerical Feature :
    
      1. Account Length
      2. Number Vmail Messages
      3. Total Day Minutes
      4. Total Day Calls
      5. Total Day Charge
      6. Total Eve Minutes
      7. Total Eve Calls
      8. Total Eve Charge
      9. Total Night Minutes
      10. Total Night Calls
      11. Total Night Charge
      12. Total Intl Minutes
      13. Total Intl Calls
      14. Total Intl Charge
      15. Customer Services Call
        
    Categorical Feature :
    
      1. State
      2. Area Code
      3. International Plan
      4. Voice Mail Plan
      
**In today's time lot of people are quitting telecom services either due to increase in a price or having any other mean of communication in a much more lower cost. I have analysed the features responsible for churn and have also recommended some ways to retain the customer's**     

**In this intensive exploratory data analysis I have tried to analyse the relationship between each features and Churn and also among features itself. You can find all different types of analysis and visualization in a notebook provided**

**Key Factor's which I believe was responsible for customer churn** - 
  
  1. Customer's who have international plan will most probably go churn which may be cause of higher cost for international plan.
  
  2. Customer's who calls during day and have higher calling minutes will go churn.

  3. Customer's who calls customer service more frequently are likely fo go churn. So it's our responsibility to troubleshoot the problem face by them as soon as possible.

  4. Customer's who don't have voice mail plan are more likely to go churn.

  5. Customer's if they incurr international charge of more than 8 are more likely to go churn.

**Recommending ways which I believe can increase the rate of customer retention** - 

  1. We must try to introduce a new scheme for international plan. By which our customer's will be benefited more than what they are geting now. Also we can decrease the cost of      our international plan as we can see those customer's who incurr international charge of more than 8 are more likely to go churn.

  2. We can introduce a service for those who calls more number of time. Like unlimited calling for certain amount of days.

  3. Also we can cut down the cost for those customer's who tends to have longer talk-time.

  4. Imporvement in customer services can be done so that churn w.r.t more number of calls doesn't get increased.

  5. We can introduce a State based plan for states where we have higher rate of customer churn.
