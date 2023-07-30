# Customer Churn Prediction & Strategy Development

## Description
This repository contains an **in-depth analysis of customer churn** in a rewards or loyalty program context. The goal is to predict and understand customer churn, and propose strategies to mitigate churn and increase retention. More specifically, this repository contains an in-depth analysis of customer churn in a rewards or loyalty program context. The main objective is to predict and understand customer churn, or 'lapse' as it's referred to in this context. The analysis includes building and evaluating several machine learning models to predict which customers are likely to churn. The models also provide insights into the key factors that influence churn, which are used to propose strategies to mitigate churn and increase customer retention.

## Contents
- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Strategies to Reduce Churn](#strategies-to-reduce-churn)
- [Conclusion and Next Steps](#conclusion-and-next-steps)
- [Business Presentation](#business-presentation)

## Project Overview
Customer churn, or lapse, is a significant concern for any business with a subscription model or loyalty program. Understanding the factors that lead to customer churn and being able to predict which customers are most likely to churn is crucial for developing effective retention strategies. In this project, we explore these issues through data analysis and machine learning. The results provide not only a predictive model for customer churn but also valuable insights into the most important factors influencing churn.

## Data Description
The data used in this analysis is customer transaction data from a rewards program. The dataset includes features such as the months since the last transaction, the sum of collected points, total money spent, years in the program, sum of redeemed points, and total money spent on redemptions.

## Methodology
We followed a systematic approach for this analysis, including:
1. Data Exploratory Analysis
2. Data Cleaning & Preprocessing
3. Feature Engineering
4. Model Building (Logistic Regression, Decision Tree, Random Forest)
5. Model Training and Evaluation
6. Model Optimization (for the Logistic Regression model)
7. Model Selection and Comparisons
8. Feature Importance Analysis

## Key Findings
The Random Forest model was the most accurate in predicting customer churn. The key features influencing churn included the time since a customer's last transaction, the total number of points a customer has collected, the total amount of money a customer has spent, the number of years a customer has been in the program, and the total number of points a customer has redeemed.

## Strategies to Reduce Churn
Based on the model's findings, several strategies were proposed to reduce customer churn:
- **Encourage regular customer** activity by sending personalized reminders and offering bonus points for transactions after a period of inactivity.
- **Expand point collection** opportunities by collaborating with new partners and increasing point awards for certain transactions.
- **Reward long-term customers** with exclusive offers and early access to sales.
- **Promote point redemption** by simplifying redemption processes and offering more redemption options.
- **Encourage higher spending** by implementing a tiered rewards system where customers earn more points for higher levels of spending.

## Conclusion and Next Steps
The detailed Jupyter notebook in this repository provides an in-depth view of the analysis process, the rationale behind the choices made, and the insights gained from the analysis. The notebook also serves as a proof of work and can be used to reproduce the analysis and findings.

## Business Presentation
For a comprehensive understanding of the analysis and the business context, please refer to the PowerPoint presentation included in the repository. The presentation provides an overview of the analysis, discusses the findings in detail, and proposes strategies to reduce customer churn based on these findings.

## Contributors

- [x] [Dimitris Matsanganis](https://github.com/dmatsanganis)



[![PowerPoint Presentation](https://img.shields.io/badge/PowerPoint-Presentation-brightgreen)](LINK_TO_YOUR_PPTX)


![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
