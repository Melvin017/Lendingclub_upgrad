# Lending Club Case Study

Lending Club, a consumer finance marketplace specializing in offering a variety of loans to urban customers, faces a critical challenge in managing its loan approval process. When evaluating loan applications, the company must make sound decisions to minimize financial losses, primarily stemming from loans extended to applicants who are considered "risky."

These financial losses, referred to as credit losses, occur when borrowers fail to repay their loans or default. In simpler terms, borrowers labeled as "charged-off" are the ones responsible for the most significant losses to the company.

The primary objective of this exercise is to assist Lending Club in mitigating credit losses. This challenge arises from two potential scenarios:

1. Identifying applicants likely to repay their loans is crucial, as they can generate profits for the company through interest payments. Rejecting such applicants would result in a loss of potential business.
2. On the other hand, approving loans for applicants not likely to repay and at risk of default can lead to substantial financial losses for the company.

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Objectives

The objective is to pinpoint applicants at risk of defaulting on loans, enabling a reduction in credit losses. This case study aims to achieve this goal through exploratory data analysis (EDA) using the provided [dataset](./loan.csv).

The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

The primary objective of this exercise is to assist Lending Club in mitigating credit losses. This challenge arises from two potential scenarios:

1. Identifying applicants likely to repay their loans is crucial, as they can generate profits for the company through interest payments. Rejecting such applicants would result in a loss of potential business.
2. On the other hand, approving loans for applicants not likely to repay and at risk of default can lead to substantial financial losses for the company.

## Conclusions

Conclusions:

Grade B Loans: Highest number of "Charged off" loans, indicating repayment challenges.

Short-Term Loans: 36-month loans had the most "Charged off" applicants, suggesting higher default rates with shorter repayment terms.

Employment Tenure: Applicants with over 10 years of employment had the highest number of "Charged off" loans, showing long-term employment does not guarantee repayment success.'

Yearly Trends: 2011 saw the highest "Charged off" loans, indicating possible economic challenges during that year.

Seasonal Patterns: "Charged off" loans peaked in the 4th quarter, especially in December, possibly due to holiday financial pressures.


## Technologies Used

- [Python](https://www.python.org/) - version 3.12.3
- [Matplotlib](https://matplotlib.org/) - version 3.9pip.0
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Collaborators

Created by [@Mittinpreet](https://github.com/) and [@Melvin John](https://github.com/)
