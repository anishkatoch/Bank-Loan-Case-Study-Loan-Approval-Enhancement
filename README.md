# Bank Loan Case Study:     Loan    Approval    Enhancement







![image](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/4d12d884-88db-4929-acbb-8414b41c3796)









## Introduction




-  In the realm of finance, bank loans play a pivotal role in providing individuals and businesses with the necessary capital to achieve their goals and aspirations. A bank loan is a financial arrangement where a borrower receives funds from a lending institution, typically a bank, with an obligation to repay the borrowed amount over a specified period, along with accrued interest.In this case study, we delve into the world of bank loans, exploring the intricate processes involved in loan approval, risk assessment, and decision-making. The analysis revolves around understanding the factors that influence a borrower's eligibility for a loan, the evaluation of creditworthiness, and the subsequent implications for both borrowers and lenders.

-  The primary objective of this case study is to uncover valuable insights into the loan application process, highlighting the critical variables that significantly impact the loan approval or rejection decision. By utilizing data-driven methodologies and analytical techniques, we aim to identify patterns, trends, and correlations that can assist lending institutions in making informed and prudent lending decisions.





## Problem Statement:


In the dynamic landscape of finance, our company specializes in providing loans to urban customers. However, we face a significant challenge where some individuals with insufficient credit history exploit this situation, leading to loan defaults. To address this issue, the primary objective of this project is to employ Exploratory Data Analysis (EDA) techniques. Through rigorous data examination, we aim to uncover patterns, trends, and insights within our loan applicant data. The overarching goal is to develop a robust system that ensures capable applicants are not unfairly rejected due to their limited credit history, while simultaneously identifying and mitigating the risk posed by those with a propensity for default. By leveraging data-driven insights, we aspire to strike a balance that not only safeguards our company's interests but also promotes financial inclusivity and fair lending practices.




## Aimed to solve:


The project aims to address the critical issue of optimizing the loan approval process in the finance industry, particularly for clients with limited credit history. By employing data analysis, this initiative seeks to distinguish between capable applicants and potential defaulters effectively. The primary goal is to develop a data-driven approach that can accurately assess an applicant's creditworthiness, thus minimizing the risk of default while ensuring that deserving individuals are not unfairly rejected. This project endeavors to provide a refined loan approval system that combines the power of data analytics with sound financial practices, ultimately promoting responsible lending and financial inclusion. By doing so, it aims to enhance the efficiency of the loan approval process, reduce default rates, and contribute to the financial stability and growth of the lending institution.





## Approach:





  1. Data Cleaning and Pre-processing: This step involves removing any irrelevant or missing data from the dataset, and formatting the data so that it can be used for analysis.

  2. Feature Engineering: This step involves creating new features or variables from the existing data that can be used to better understand the movies. For example, creating a new variable that represents the budget of the movie, or creating a new variable that represents the genre of the movie.

  3. Exploratory Data Analysis (EDA): This step involves visualizing the data to understand the distribution of different variables and identify any patterns or trends in the data.

  4. Data Visualization: This step involves creating visual representations of the data, such as bar charts, line plots, and scatter plots, to help understand the data and draw insights.

  5. Conclusion and Recommendation: This step will be the final step where the data is presented in an understandable way and conclusion is made based on the analysis.




## Univariate Analysis


- ### DEFAULTER

![housing 1](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/281517a3-435c-4f47-a550-fb82132ae946)


- ### NON DEFAULTER


![housing 0](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/a64c892d-3e77-4bad-94c0-67b533109917)


## Bivariate Analysis


- ### DEFAULTER AND NON DEFAULTER


![F1](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/91746ac6-698f-42ca-b434-51f1ac543b4b)



## Segmented Analysis


![S10](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/853b4f55-2132-4cfc-955a-c7d502931776)



## Top 10 Correlation

- ### DEFAULTER

![1](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/a83eb683-a344-46b9-9a9b-a4f4d449668c)


- ### NON DEFAULTER 

![0](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/5c7dda8e-0dd9-41f9-b27c-a230bec3ef6c)


## Previous Loan Status

- ### CLIENT TYPE






![CLIENT](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/6900fba6-c3ba-44cf-8cc4-46a9b9db8b21)















- We can see that the Defaulters are more for previously Unused offers loan status clients, who were New.
- For previously Approved status, the New clients were more defaulted followed by Repeater.
- For previously Refused applicants, the Defaulters are more Refreshed clients.
- For previously Canceled applicants, the Defaulters are more New clients.



- ### GENDER

![GENDER](https://github.com/anishkatoch/Bank-Loan-Case-Study/assets/130006013/73b85cfa-d55c-4177-b131-7a1df9b9a48c)



- We see that previously Refused clients are more likely to default compared to previously Approved clients.
- Additionally, in all cases, males have a higher default rate than females.




## Insights:


### A. Decisive Factors for Repayer Applicants:
1. **NAME_EDUCATION_TYPE:** Academic degree has fewer defaults.
2. **NAME_INCOME_TYPE:** Students and businessmen have no defaults.
3. **ORGANIZATION_TYPE:** Clients with Trade Type 4 and 5 and Industry Type 8 have defaulted less than 3%.
4. **AMT_INCOME_TOTAL:** Applicants with Income more than 700,000 are less likely to default.
5. **CNT_CHILDREN:** People with zero to two children tend to repay the loans.



### B. Decisive Factors for Defaulter Applicants:
1. **CODE_GENDER:** Men are at relatively higher default rates.
2. **NAME_FAMILY_STATUS:** People who have civil marriage or who are single default a lot.
3. **NAME_EDUCATION_TYPE:** People with Lower Secondary & Secondary education.
4. **NAME_INCOME_TYPE:** Clients who are either on maternity leave or unemployed default a lot.
5. **OCCUPATION_TYPE:** Avoid Low-skill Laborers, Drivers and Waiters/barmen staff, Security staff, Laborers, and Cooking staff as their default rate is significant.
6. **CNT_CHILDREN:** Clients who have children equal to or more than 9 default 100%, and hence their applications are to be rejected.
7. **AMT_GOODS_PRICE:** When the credit amount goes beyond 3 lakhs, there is an increase in defaulters.




## Suggestions:

1. **Repayment Rate of Previously Cancelled Clients:** Record reasons for cancellation to determine and negotiate terms with repaying customers in the future for increased business opportunities.

2. **Conversion of Rejected Clients to Repaying Clients:** Document reasons for rejection to mitigate business loss and approach them again for further loan offers.



## Results:

1. **Housing Type Influence on Default Rates:** Majority of loan applications are from people living in rented apartments or with parents, requiring careful credit assessment to reduce default risk.

2. **Impact of Loan Amount on Default Rates:** Clients availing loans in the 3-6 Lakhs range have a higher tendency to default, consider applying higher interest rates for this credit range.

3. **Income Level and Default Probability:** Most applications are from individuals with total income less than 3 Lakhs, who have a higher probability of defaulting. Offer loans to this income group with higher interest rates.

4. **Effect of Number of Children on Default Rates:** Clients with 4 to 8 children have a significantly higher default rate, consider imposing higher interest rates on loans for this group.

These insights can help the bank make informed decisions and improve its loan policies for better risk management and business growth.


## Conclusion:

- The Bank loan approval process and the criteria followed by the agencies to approve or reject loan applications from different clients have been thoroughly understood.
- This aspect of the banking process is among the busiest, as many individuals are in need of financial assistance and require loans to afford various expenses beyond their current bank balance capabilities. Consequently, it becomes the agencies' responsibility to carefully evaluate and decide which loan applications to approve and which ones to reject.
- The banking sector, particularly the loan industry, is a highly successful and stable industry, generating billions in revenues and supporting the livelihoods of millions of people. Ensuring the constant stability and continuity of this specific part of the banking sector is crucial.
- The project has facilitated making tough decisions regarding dropping certain columns, changing values, and refining data, providing insights into real-life problems that can arise in the banking sector due to data unavailability.
- This project has enabled the practical application of theoretical knowledge of Excel, enhancing skills and understanding of data analysis in the context of the banking industry.
- Overall, this project has shed light on the complexities and significance of the loan approval process and data analysis in the banking sector, underscoring the importance of informed decision-making for the continued success and growth of the industry.




## Limitations:



1. **Data Source and Quality:** The quality and reliability of the dataset used for analysis are critical. If the data contains errors, biases, or missing values, it can lead to inaccurate insights and decisions.

2. **Data Representativeness:** The dataset may not fully represent the entire population of loan applicants. Biases in the data, such as underrepresentation of certain demographics or regions, can affect the generalizability of the findings.

3. **Limited Context:** The project provides insights into loan approval factors but may lack contextual information about external economic factors, regulatory changes, or market dynamics that could impact loan decisions.

4. **Assumption of Causality:** Correlations between variables do not necessarily imply causation. While the project identifies factors correlated with loan defaults, establishing causality would require more in-depth research.

5. **Model Validation:** If predictive models are used, their accuracy and generalizability need to be rigorously validated to ensure their reliability in real-world scenarios.




## Challenges:




1. **Data Volume:** Managing and analyzing a large dataset with 24 lakh (2.4 million) data points can be computationally intensive and may require specialized infrastructure for efficient processing.

2. **Data Cleaning and Pre-processing:** Cleaning and preparing such a vast dataset can be time-consuming and challenging, requiring thorough data accuracy and consistency checks.

3. **Data Visualization:** Designing effective visualizations to convey insights from a dataset with numerous columns and variables can be a significant challenge, especially when dealing with complex financial data.

4. **Interpreting Complex Results:** Interpreting and communicating the results of complex data analysis, especially with a dataset of this size, can be challenging, requiring clear and actionable insights for decision-makers.


