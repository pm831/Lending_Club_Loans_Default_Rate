# Lending Club Loans Data Exploration
## Loan Statuses Demographic Analysis

![Lending_Club_Loans_Analysis](https://user-images.githubusercontent.com/19572673/57266477-155fc700-704a-11e9-88f3-afe81df3606c.PNG)

## Use Case:
### Figuring out specific causes of loan defaults by specific factors to make better long term decisions
## Initial Dataset:
### Loan Dataset
## Software:
### PowerBI
## Basic Steps:
#### Downloaded the dataset. 
#### Categorical slicers include State, Zip, ID, Term, Grade, Sub-Grade, Employer, Employer Length, Home Ownership, Verification Status, Loan Status, Loan Purpose. Numerical slicer includes the 'date range' (where you can slide accordingly)
##### State: 
##### Zip: 
##### ID:
##### Term: 
##### Grade:
##### Sub-Grade:
##### Employer:
##### Employer Length:
##### Home Ownership:
##### Verification Status:
##### Loan Status:
##### Loan Purpose:
##### Date Range:
![Lending_Club_Loans_Analysis_Slicers](https://user-images.githubusercontent.com/19572673/57423158-d4e68180-71e0-11e9-9f81-4caaeed99774.PNG)
#### Tabular reports include by State, Zip, Loan Grade, Loan Sub-Grade Metrics, Employer Length, Home Ownership, Loan Purpose, Loan Status, and by specific ID. 
##### State Metrics
##### Zip Metrics
##### Loan Grade Metrics:
##### Loan Sub-Grade Metrics
##### Employer Length Metrics:
##### Home Ownership Metrics:

![Lending_Club_Loans_Analysis_Reports](https://user-images.githubusercontent.com/19572673/57493298-52b69580-7292-11e9-9f7a-377d8807c6a4.PNG)
#### Calculated measures (KPIs):
##### _Average_Income = sum(LoanData[annual_inc])/count(LoanData[id])
![Lending_Club_Loans_Analysis_Income_KPI](https://user-images.githubusercontent.com/19572673/57495391-e80a5780-729b-11e9-8950-bbe980a85caa.PNG)
##### _Average_Int_Rate = sum(LoanData[int_rate])/count(LoanData[id])
![Lending_Club_Loans_Analysis_IR_KPI](https://user-images.githubusercontent.com/19572673/57495392-e80a5780-729b-11e9-8faa-6d9f3846a57a.PNG)
##### _Average_Loan_Amount = sum(LoanData[loan_amnt])/count(LoanData[id])
![Lending_Club_Loans_Analysis_LA_KPI](https://user-images.githubusercontent.com/19572673/57495393-e80a5780-729b-11e9-8843-381847bd0adf.PNG)
##### _Average_DTI_Amount = sum(LoanData[dti])/count(LoanData[id])
![Lending_Club_Loans_Analysis_DTI_KPI](https://user-images.githubusercontent.com/19572673/57495390-e80a5780-729b-11e9-849d-0b7c20444de8.PNG)

