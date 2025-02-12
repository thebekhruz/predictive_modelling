## Loan Default Dataset - Column Descriptions

[|](EDA)

  
### **Basic Loan and Application Details**

- **ID**: Unique loan application identifier.

- **year**: Year of loan application.

- **loan_limit**: Indicates if the loan is within conforming limits ("cf" = conforming).

- **approv_in_adv**: Pre-approval status ("pre" = pre-approved, "nopre" = not pre-approved).

- **loan_type**: Type of loan.

- **loan_purpose**: Purpose of the loan.

- **Credit_Worthiness**: Applicant’s creditworthiness level.

  

### **Applicant and Co-Applicant Details**

- **Gender**: Applicant’s gender ("Male", "Female", "Joint").

- **age**: Age group of the applicant.

- **Credit_Score**: Applicant’s credit score.

- **credit_type**: Credit bureau providing the credit score (e.g., Experian, Equifax).

- **co-applicant_credit_type**: Credit bureau for the co-applicant.

  

### **Loan and Business Details**

- **open_credit**: Existing open credit lines.

- **business_or_commercial**: Whether the loan is for business purposes.

- **LTV (Loan-to-Value Ratio)**: Loan amount compared to the asset value.

- **dtir1 (Debt-to-Income Ratio - DTI)**: Ratio of applicant’s debt payments to income.

  

### **Application Process and Approval**

- **submission_of_application**: How the application was submitted.

- **Security_Type**: Whether the loan is secured by collateral.

- **Region**: Applicant’s geographic region.

  

### **Target Variable**

- ~~**Status**: Indicates loan default (1 = Defaulted, 0 = Not Defaulted).~~ Correction was made after visualising the data.

- **Status**: Loan repayment status:

- **0** = Full repayment (no default).

- **1** = Default (loan not repaid).

  

---