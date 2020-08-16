# Prosper Exploratory Analysis


## Dataset

The data consists of information regarding 113,937 loans granted by Prosper, including Prosper score or borrower risk, listing category or loan type, employment status, number of current credit lines, number of open revolving accounts, debt to income ratio, and original loan amount. The dataset can be found in Udacity's 
repository [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv),
with feature documentation available [here](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub?embedded=True).




## Summary of Findings

In the exploration, I found several interesting relationships between the dependent variable (LoanSatus) and these selected borrowers features: Prosper score or borrower risk, original loan amount, and debt to income ratio. I choose to present only the loan statuses distribution and its relationship with the variables listed above, but debt to income ratio. The reason for my decision was to improve the storytelling follow and generate meaningful insights.

Regarding the relationship between loan status and debt to income ratio,  I noticed that loans completed or about to be finalized (FinalPaymentInProgress status) presented the lower debt to income ratio than the remaining loan status.

Additionally, employed borrowers had the highest amount of charged-off loans that borrowers under the remaining employment status, which was the opposite of my expectations. 


## Key Insights for Presentation

For the presentation, I focus on just the influence of borrowers risk and original loan amount into the loan statuses. I start by introducing the loan status variable, followed by its relationship with borrowers risk (ProsperScore) and the original loan amount. 

To analyze the relationships mentioned above, I decided to use box plots because they provide all the statistical information required throughout this project.
