## Exploratory Data Analysis (EDA)

### Introduction

This project aims to apply Exploratory Data Analysis (EDA) techniques to a real-world business scenario in the banking and financial services sector. The objective is to analyze loan application data to understand patterns that can help minimize the risk of financial loss while lending to customers.

### Business Understanding

Loan providers often face difficulties in assessing applicants with insufficient or non-existent credit history. Some consumers take advantage of this and default on their loans. The goal of this analysis is to ensure that applicants capable of repaying the loan are not mistakenly rejected, while minimizing approval of high-risk applicants who may default.

### Key Risks in Loan Approval:

 - Loss of Business: Rejecting applicants who are likely to repay the loan.
 - Financial Loss: Approving applicants who are likely to default.
 - The dataset includes information on loan applications and applicant financial history. The study aims to identify factors that influence loan defaults to help financial institutions make informed lending decisions.

### Business Objectives

 - The primary objective of this analysis is to identify key indicators of loan default, enabling financial institutions to:
 - Deny loans to high-risk applicants.
 - Adjust loan amounts based on risk assessment.
 - Offer higher interest rates to risky applicants.
 - By analyzing consumer and loan attributes, we aim to extract meaningful patterns that drive loan defaults.

### Data Understanding

The dataset consists of three files:

 - application_data.csv – Contains information about applicants at the time of loan application.
 - previous_application.csv – Contains details of applicants' previous loan history, including application outcomes.
 - columns_description.csv – A data dictionary explaining the variables in the dataset.

The analysis will focus on exploring these datasets to uncover trends and relationships between consumer attributes and loan default rates.

## Key Findings

#### Rejections

 - Most loan rejections came from the purpose 'Repairs'.
 - Loan applications for education purposes have an equal number of approvals and rejections.
 - Loan purposes such as 'Paying other loans' and 'Buying a new car' show significantly higher rejection rates compared to approvals.
 - Difficulty Paying Loans
 - Loan purposes categorized under 'Repairs' face more difficulties in on-time payments.

Some loan purposes have significantly higher successful payments with minimal payment difficulties, including:

 - 'Buying a garage','Business development','Buying land','Buying a new car','Education'
 - These purposes can be prioritized for better repayment rates.

#### Credit Analysis

 - Higher credit amounts are associated with loan purposes such as: 'Buying a home', 'Buying land', 'Buying a new car', 'Building a house'
 - Income type 'State Servants' have a significant amount of credit applied.
 - Loan purposes related to 'Money for a third person' or a 'Hobby' have lower credit applications.
 - Office apartments have higher credit with successful repayments (target 0).
 - Co-op apartments have higher credit with unsuccessful payments (target 1), indicating higher risk.
 - Banks should avoid lending to applicants with housing type Co-op apartments due to payment difficulties.
 - Housing types such as With parents, House/Apartment, and Municipal apartment have more successful payments and can be prioritized.

### Recommendations
 - Focus on contract types: Banks should prioritize lending to 'Students' and 'Pensioners' as they show lower default rates.
 - Reduce risk from 'Working' income type: This group has the highest number of unsuccessful payments.
 - Avoid lending for 'Repairs': This loan purpose has a higher number of defaults.
 - Prioritize clients from 'With Parents' housing type: These applicants have the least number of unsuccessful payments.

### Conclusion

By analyzing loan and consumer attributes, we identified key drivers of loan default. Financial institutions can leverage these insights to make better lending decisions, optimize risk assessment, and reduce financial losses while ensuring profitable loan approvals.

