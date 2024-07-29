# Churn Rate

## Project description

In this project with information from Databel (a telecom company in the US), we get to analyze a large dataset including demographical details from clients to visualize metrics about the clients' preferences and disclose the foundations of their decisions regarding churning, unsubscribing, and changing services.

## Objective

Figure out why customers are churning at the rate they are, by visualizing the dataset and calculating new measures that enable the understanding of tendencies. Create an eye-catching report in PowerBI.

## Data dictionary | Metadata

| **Customers status** |  |
| ----------------|---------------------------------------------|
| Customer ID     | The unique ID that identifies a customer |
| Churn Label     | Contains "Yes" or "No" to indicate if a customer churned |
| Churn Reason    | The particular reason why the customer ended the contract |
| Churn Category  | Groups multiple churn reasons together for analysis purposes |


| **Demographics** |  |
| -----------------|----------------------------------------------|
| Gender     | The gender of the customer, indicated by "Male", "Female" |
| Under 30   | Indicates if the customer is under 30 with "Yes" or "No" |
| Senior     |  Indicates if the customer is 65 or above with "Yes" or "No" |
| Age        | The age of the customer |


| **Contract information** |  |
| -------------- | --------------- |
| Contract Type   | Contains "Month-to-Month", "One Year" or "Two years" |
| Payment Method   | Preferred payment method of the customer indicated <br> with "Credit Card", "Direct Debit" or "Paper Check" |
| State            | The code of the state where the customer lives |
| Phone Number   | Phone number of the customer |
| Group          | Indicates if the customer is part of a group contract. <br> A group Contract offers advantages and is generally cheaper. |
| Number of <br> customers in <br> a group | Number of customers part of the group |


| **Subscription types & Charges** |  |
| ------------------------------ | -----------|
| Account length <br> in months | The number of months the customer has been with Databel |
| Local Calls                   | Amount of local (within the US) calls from the customer |
| Intl Calls     | Amount of international (outside the US) calls <br> from the customer |
| Intl Mins     | The number of minutes spent calling internationally. <br> Intl Active: Indicates if the customer called <br> internationally with a "Yes" or "No" |
| Intl Plan     | Indicates if the customer has a premium plan to <br> call internationally for free with "Yes" or "No". This <br> premium is reflected in the monthly charge. |
| Extra International <br> charges     | Contains the extra charges for international calls <br> for customers who are not on an international plan |
| Customer Service <br> Calls | The number of calls made to customer service |
| Avg Monthly GB <br> download | Contains the average monthly download volume <br> in gigabytes |
| Unlimited Data <br> Plan| Indicates that the customer has free unlimited <br> download capacity with "yes" or "No". This premium <br> is reflected in the monthly charge. |
| Extra Data Charges | Contains the extra charges for data downloads for <br> customers who are not on an unlimited plan |
| Monthly Charges    | Average of all Monthly Charges to the customer |
| Total Charges | Sum of all monthly charges |

## Log

1. Exploratory analysis: 
  - Data checking
  - Churn calculations
  - Digging into churn categories
2. Calculation of new variables and columns to understand churn
3. Track tendencies: 
  - Demographics analysis
  - Age grouping
  - Zooming out
  - Exploration of Unlimited plan, International calls, Contract types.
4. Visualizing the analysis: 
  - Dashboarding geographic trends with maps
  - Splitting age brackets and groups
  - Diagram payment method, contract categories, international and data plans.

## Conclusions

### Business Intelligence Analysis: Churn Rate Insights

1. **Age-related Churn Trends**
   - Senior citizens (60+ years) have a churn rate of 38.46%, compared to 24% for younger customers.
   - Churn rate peaks among users aged 80+, reaching 52%. 
   - Users aged 20-60 have an average churn rate of 24%, which steadily increases with age.

2. **Contract Duration and Churn**
   - Monthly contracts exhibit a significantly higher churn rate of 46.29% compared to 6.62% for yearly contracts.
   - Over half (51%) of Databel clients are on monthly contracts.
   - Churn rates in monthly contracts remain high regardless of contract length, with rates such as 57% for 8 months, 28% for 16 months, and nearly 54% for 18.75 months.
   - Yearly contracts show a decrease in churn rates over time, with 8% for contracts active for 35 months.

3. **Contract Groups and Churn**
   - Clients in contract groups (2-6 people) have an average churn rate of 8%.
   - Those not in a group pay about €11 more and have a higher churn rate of 32%.

4. **Unlimited Data Plans and Usage**
   - Users with unlimited data plans but using less than 5 GB per month have a churn rate of nearly 35%.
   - Those using 5-10 GB per month also have a high churn rate of 33%.
   - Clients using 10 GB or more have a lower, but still significant, churn rate of 27%.

5. **Primary Reason for Churn**
   - The most common reason for customers leaving is better offers from competitors.

These insights highlight key areas for potential intervention to reduce churn, such as addressing pricing structures for senior citizens, offering incentives for longer contract durations, promoting contract groups, and tailoring unlimited data plans to actual usage.
