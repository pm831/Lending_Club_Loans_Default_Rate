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
##### Average Income = sum(LoanData[annual_inc])/count(LoanData[id])
![Lending_Club_Loans_Analysis_Income_KPI](https://user-images.githubusercontent.com/19572673/57495391-e80a5780-729b-11e9-8950-bbe980a85caa.PNG)
##### Average Int Rate = sum(LoanData[int_rate])/count(LoanData[id])
![Lending_Club_Loans_Analysis_IR_KPI](https://user-images.githubusercontent.com/19572673/57495392-e80a5780-729b-11e9-8faa-6d9f3846a57a.PNG)
##### Average Loan Amount = sum(LoanData[loan_amnt])/count(LoanData[id])
![Lending_Club_Loans_Analysis_LA_KPI](https://user-images.githubusercontent.com/19572673/57495393-e80a5780-729b-11e9-8843-381847bd0adf.PNG)
##### Average DTI Amount = sum(LoanData[dti])/count(LoanData[id])
![Lending_Club_Loans_Analysis_DTI_KPI](https://user-images.githubusercontent.com/19572673/57495390-e80a5780-729b-11e9-849d-0b7c20444de8.PNG)
##### Loan Status Distribution
![Lending_Club_Loans_Analysis_Loan_Status](https://user-images.githubusercontent.com/19572673/57498385-ada7b700-72a9-11e9-8edd-2769be9153d1.PNG)
##### Loan Grade Distribution
![Lending_CLub_Loans_Analysis_Loan_Grade](https://user-images.githubusercontent.com/19572673/57498384-ada7b700-72a9-11e9-8188-53db4fefd16e.PNG)
##### Employer Length Distribution
![Lending_Club_Loans_Analysis_EL](https://user-images.githubusercontent.com/19572673/57498383-ada7b700-72a9-11e9-9c19-5ce61d21168d.PNG)
##### Home Ownership Distribution
![Lending_Club_Home_Ownership](https://user-images.githubusercontent.com/19572673/57498382-ada7b700-72a9-11e9-957f-6f2523d9f6c1.PNG)
#### Loan Purpose
![Lending_Club_Loan_Purpose](https://user-images.githubusercontent.com/19572673/60401056-14c74680-9b4a-11e9-9298-f67a17c114ba.PNG)
#### Word Cloud

#### Monthly Trend

