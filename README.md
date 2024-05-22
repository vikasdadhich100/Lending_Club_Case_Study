# Project Name
> Lending Club Case Study


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Lending Club Case Study
Team : [Vikas Dadhich](https://github.com/vikasdadhich100), [Vinayak SG](https://github.com/yesgvinayak) Date : 22 May 2024

We have a dataset loan.csv The data given below contains information about past loan applicants and whether they ‘defaulted’ or not.

**Business understanding**
The data is shared to make decision after reciving the application basd on Applicant profile. This involves Risk factors based on loss to the company, If a candidate repay the loan ammount or not.

We need to understand if an applicant is defaulted or non-defaulted based on the data for past loan application. We need to find the person is likely to defauled based on we can define our below actions to avoid Risks.

Denying loan
Reducing loan Amount
Lending at highest interest rate
We need to collect data based on consumer attribute and loan attributes.

**Business Goal**
Reduce the risk and make sure collect the data in to take decision on the loan application to avoid financial loss.

**Note:** the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on the provided analysis, several risk factors for lending loans can be identified:
- **Loan Amount:** Larger loan amounts significantly increase the likelihood of defaulting. Higher-value loans require careful assessment of borrower capacity and stringent risk management practices.

- **Loan Term:** Borrowers opting for longer loan terms, such as 60 months, exhibit higher default rates compared to those choosing shorter terms like 36 months. Encouraging borrowers to opt for shorter terms can mitigate default risk.

- **Interest Rate:** There's a critical threshold between 10-17% interest rates where the risk of default is heightened. Loans with rates above 10% show increased default rates, peaking before declining again after 17%. Monitoring and managing loans within this range is crucial to mitigate default risks.

- **Employment Tenure:** Borrowers with extreme employment tenures, either very new or very experienced, show higher default rates. Targeted risk assessment and mitigation strategies are needed for these groups.

- **Income:** Lower-income borrowers, especially those earning between 40,000 and 60,000, exhibit a higher risk of default. Targeted risk management strategies are necessary for this income group.

- **Debt-to-Income (DTI) Ratio:** Borrowers with higher DTI ratios are at an increased risk of defaulting. DTI with 12-17 have higher number of defaulted loan but higher dti has higher chance of defaulting.

- **Seasonal Trends:** There are seasonal trends in loan borrowing and repayment behavior. Understanding these patterns can help anticipate potential default risks during certain months.

  - Month 1, 5 and 9 Has the high charged off comaritively similarity Fully paid in the other months

  - Month 2,4,7 and 8 has less charged off comparitively similarity Fully paid in the other months

- **Loan Grade and Sub-categories:** Grades A and B show favorable performance with lower charge-off rates, while categories E and F demonstrate comparatively higher charge-off rates. Sub-categories A1-A5 and B1-B5 exhibit better repayment records compared to E1-E5 and F1-F5 .

- **Loan Purpose:** Debt_consolidation is the primary purpose for borrowing loans. Understanding borrower motivations can help assess their ability to repay.

- **Overall Default Rate:** While around 15% of loans have been charged off, the majority (approximately 85%) have been fully paid. Despite this favorable trend, careful risk assessment and management remain essential.

- **Verification:** Unverified borrowers may present higher default risks due to potential inaccuracies in their financial profiles, necessitating additional risk management measures.

- **Public Recorded Bankruptcy:** The majority of borrowers and defaulters having no record of public recorded bankruptcy suggests a lower prevalence of extreme financial distress among borrowers. This may indicate a lower overall risk of default compared to populations with higher bankruptcy rates.

Considering these factors collectively and integrating them into the lending decision-making process can help mitigate default risks and ensure responsible lending practices.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Google Collab](https://colab.research.google.com/?authuser=0#create=true)
- Python 3.0 
- Pandas 2.0.3
- Seaborn 0.13.1
- Matplotlib 3.7.1
 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on [AI/ML PG Course](https://learn.upgrad.com/).


## Contact
Created by [@vikasdadhich100]/vikasdadhich1990@gmail.com and [@yesgvinayak]/vinayaksg01@gmail.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

