## Churn Data Modelling Project
In Bank Tableau story I investigated and explored data set of bank in countries such as France, Germany and Spain. I came up with the insights and draw useful conclusions. Which customers are leaving the bank, residing in which particular region or of age group? The data is randomly selected total of ten thousand customers on which Ad-hoc A-B testing is conducted using various Dimensions and Measures.
The Churn Modelling data set can be found [here] (https://www.superdatascience.com/training/):

My Tableau workbook for Churn Data Modelling can be found [here] (https://public.tableau.com/profile/sim6166#!/):

**Gender A-B test-** For this test, Gender and Exited is used to know who will most likely exit the bank either males or females.

> Analysis- The percentage of Male customer who left the bank is only 16% which is less than the female customers exiting at 25%. It is concluded that female customers are more likely to exit the bank than the male customers.

**Geography/Country Analysis-** The customers in Germany (32% exited) are leaving the bank at higher rate. The reason can be the presence of any competitor in that country, the products are up to customers’ needs or any other reason.

**Credit Card and Customer Analysis-** It gives only 1% difference between customers having a credit card and customers not having credit card with the bank. This variable does not give any significant insight to come up with any conclusion. Customers who are actively logging in and using features of bank are less likely to leave the bank as compared to non-active customers.

**Number of Products Analysis-** Only 1% people left with 2 products and 28% left the bank with 1 product of bank. 

>Anomalies- On the other side, anomalies can be seen where customers with 3 or 4 products are leaving the bank at rapid rate of 83% and 100%, respectively. This anomaly could be the result of sample selected for analysis. The total number of records for customers with 3 and 4 products are 266 and 60, respectively.  

> Validation- The data be validated by finding a variable that ensure that it does not affect the end result. I run a test on it, by creating a calculated field on Customer Id’s last digits. It gives a uniform result with customers with same digit has same probability of leaving the bank as average of 20% with some fluctuations. This validated the approach as well as the sample data set selected for the analysis. 

**Age analysis-** The demographic of bank customers is mostly between the age group of 30 to 40. It is visualized in the tableau workbook using bins. It is visualized the people on the lower and higher age band are less likely to leave the bank. Customers between the age group of 45 and 60 are leaving the bank above average of 20%. 
> Validation using Chi-Squared test- The results are validated to be statistical significant by conducting Chi-squared test using online tools as well as MS Excel, which gave the same result as visualized from Tableau workbook.
The link to online tools 
https://www.evanmiller.org/ab-testing/chi-squared.html
http://vassarstats.net/newcs.html
**Balance and Estimated Salary Analysis –** these variables does not have much impact on the likelihood of a person to leave the bank. Balance bins and Estimated Salary gives an average of 20% exit level of customers with some fluctuations in it. 
 

