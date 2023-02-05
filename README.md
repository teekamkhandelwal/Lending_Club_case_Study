# Lending_Club_case_Study
**LENDING CLUB -** Lending club is a platform that provide the loan based on pepole credit profile and historical data on some interest rate.

![image](https://user-images.githubusercontent.com/72481400/216401114-b7bee350-abb9-42c1-b8b8-700e27fa60a9.png)  
                                     [1]

# Objective\Purpose
Purpose of this case study to provide help in taking decision of consumer financial company to approved loan or not based on persons historical data(Profile Data).

# Project Discription
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
 
 * If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
 * If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. 

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

![image](https://user-images.githubusercontent.com/72481400/216405337-152fb141-62c8-47a3-ae80-61a865d04a16.png)

When a person applies for a loan, there are two types of decisions that could be taken by the company:

* Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

  * Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
  * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
  * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

* Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)


## Introduction - 
Data analysis of this case study categriesed in following steps-
* Data cleanning
* Univariate Analysis
* Bivariate/Multivariate Analysis
* Result



### Method Used
* Exploratory Data Analysis(EDA)
* Data Visualization 

### Technology Used
* Python
* Pandas
* Juipter 
* NumPy
* Metplotlib 
* missingno
* seaborn etc.





# Conclusions/Suggestions

1) Lending club shuold consider to accepting more loans request less then 10% interest rate as their probabity of charged_off is have lesser.

2) Lending club shuold consider to accepting more loans request for borrowers which owning house their have lees probabilty to Charged_off.

3) Lending club shuold consider to accepting more loans request for grade A respect to B C D becuase in B C D E have lots off Charged_off

4) Lending club shuold consider to accepting more loans request of borrowers which have annual income gretaer then 90000 its charged_off % have nearest 10%.

5) Lending club need to accept more loan for 36 month term there have less chances of charged_off and it continuously increasing year by year.

6) Lending club need to accept loan which owning house, annual income have greater then 90000, interest rate is less then 10%.This combination is have less chances to charged_off.

7) Lending club should accept more loan request of borrowers which one have source verified or verified. Their have less chance of charged_off.

8) Lending club should accept more loan request of borrowers which one have employment experienc less then 10 years.

9) Lending club should accept more loan for applied for wedding, major_purchase, car and credit_card here have chances of charged_off is less nearest 10% but for small business have 27.97% charged_off.

10) Lenading club should accept the loan request for small loan amount For loan amount till 14K charged_off(nearest 13%) have low risk

11) Lenading club should accept the loan request for coming from addres state IN IA and ME here having low risk of charged off.



# Contributer
* Teekam Chand Khandelwal
   email id: teekamkhandelwal@gmail.com  
  
# Refrences
[1] https://d3.harvard.edu/platform-digit/submission/lending-club-a-marketplace-for-loans/ 
   
**Note:- Data used for this project persent in data folder.**
