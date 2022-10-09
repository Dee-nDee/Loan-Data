# Loan Data from Prosper Exploration

## Dataset

The data originally consists of information regarding over 110,000 loan entries on 81 variables.
For this analysis though, it was modified to 14,882 loan entries on 13 variables including
the loan amount, interest rate, loan length, loan listing category, loan status, 
borrowers' income range and other characteristics of borrowers. The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554484977407000).

During the exploration of the dataset, univariate, bivariate and multivariate visualizations 
were created to get a good understanding of individual variables, 
find relationships between pairs/groups of the variables, and to 
obtain a better understanding of the relationships.


## Summary of Findings

A large number of the loans are mid term loans, 
and generally, the loan amount increases as the income range of the borrower increase.

An interesting relationship was found between the loan amount and interest rate. 
The relationship between both variables is negative. 
As the loan amount increase, the interest rate decreases. 

Also, a relationship was found between loan length, 
loan amount, interest rate, and loan status.
The relationship between loan amount/interest rate and loan length is positive. 
As the loan length goes from short term to long term, 
there is an increase in the loan amount and interest rate. 
For each loan length, as stated earlier, as the loan amount increases, 
there is a decrease in interest rate. 
Also, for all loan lengths, most loans with higher interest rates are usually either not paid in time, 
become defaulted or are charged off, and lower loan amounts are usually defaulted or charged off. 

The majority of loans taken are for debt consolidation, 
and they are mostly taken by high-income earners ($75,000-100,000+). 
Lastly, 75.34% of the loans taken for student use are usually completed, 
19.26% are charged off, and only 5.41% of the student use loans default.

Except for the most frequent loan length finding, 
and the relationship found between the loan amount and interest rate, 
the rest of the exploratory findings discussed above will be in the explanatory presentation.


## Key Insights for Presentation

During the exploratory analysis of the dataset, 
the insights stated below were obtained. 
These findings offer a clear understanding of the data and will be conveyed in the explanatory report.

- Most loans taken for student use are usually completed.

- High-income earners are more likely to take loans for debt consolidation. 

- Loans with longer loan length have a higher interest rate. 

- Borrowers who take high loan amounts are more likely to opt for long-term loans. 

- High-income earners are more likely to take high loan amounts.

- Lower loan amounts for each loan length, are more likely to be defaulted or chargedoff. 

- For each loan length, loans with higher interest rates will likely get defaulted, charged off or not paid in time. 

