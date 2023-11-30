# Home Credit Scorecard Model

## Project Description

This project is a virtual internship project conducted by Rakamin Academy in collaboration with Home Credit Indonesia as part of the data science bootcamp program I am enrolled in at Rakamin Academy.

## Data Source

The dataset used for this project is available on Kaggle as part of the competition organized by Home Credit in 2018. You can access the data source page [here](https://www.kaggle.com/competitions/home-credit-default-risk/data).

## Background

Home Credit focuses on promoting financial inclusion for the unbanked population, protecting them from bad lenders. Data scientists are invited to optimize their data using statistical methods and machine learning. The objective is to avoid denying credit to qualified clients and offer loans with terms conducive to successful repayment.

## Objective

Develop a robust machine learning model with the capability to predict customers' creditworthiness and minimize rejections for those with the ability to repay.

## Metric

**ROC AUC:** Given the emphasis on ensuring a positive loan experience for the underserved population and avoiding the rejection of clients capable of repayment, while also considering the overall success of the clients, the key focus should be on optimizing ROC AUC. In the context of credit risk modeling, ROC AUC measures the model's ability to distinguish between the positive and negative classes, providing a comprehensive assessment of its discriminative power.

## Tool

**Jupyter Notebook**

## Libraries

Package/Library Requirements:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
- imblearn
- xgboost
- lightgbm
- scipy

## Results

Among the 5 models utilized, namely logistic regression, decision tree, random forest, xgboost, and lgbm, it was found that the **logistic regression** model outperformed the others with the following scores:

- **Accuracy of the logistic model:** 0.6866
- **AUC score of the logistic model:** 0.7325
- **Precision:** 0.15
- **Recall:** 0.15
- **F1:** 0.25

Logistic regression excelled in three metrics compared to the other models: **roc_auc** (the primary metric), **recall**, and **f1**.

## Acknowledgement

In the completion of this project, I drew inspiration and information from several online sources, including:

- [Start Here: A Gentle Introduction](https://www.kaggle.com/code/willkoehrsen/start-here-a-gentle-introduction)
- [Home Credit Default Risk Recognition](https://github.com/abhishekdbihani/Home-Credit-Default-Risk-Recognition)
- [Home Credit Risk Assessment](https://github.com/imane-ayouni/Home-Credit-risk-assessment)
- [Multicollinearity - Investopedia](https://www.investopedia.com/terms/m/multicollinearity.asp#:~:text=Multicollinearity%20is%20a%20statistical%20concept,in%20less%20reliable%20statistical%20inferences.)

---
