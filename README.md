# TelecomChurn
> In the telecom industry, customers can choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining highly profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

In this competition, your goal is to build a machine-learning model that can predict churning customers based on the features provided for their usage.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)

## General Information
- **Background:** In the telecom industry, customers can choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate.
- **Business Problem:** This project goal is to build a machine learning model that can predict churning customers based on the features provided for their usage.

## Conclusions
- Overall accuracy will be the primary evaluation metric for the telecom churn model: We observe that the models 'Logistic Regression with RFE', 'Logistic Regression with PCA', 'Decision Tree with PCA', and 'AdaBoostClassifier' overall accuracy is good. But models 'Random Forest Classifier with PCA and Hyperparameter Tuning', and 'XGBoost Classifier' have more accuracy.
- Also consider other metrics like precision, recall, etc. for the different models that can be used for evaluation purposes based on our business objective to identify customers who'll churn with more accuracy than the ones who'll not churn: We observe that the models 'Logistic Regression with RFE', and 'Logistic Regression with PCA' have good sensitivity or recall metrics compared to other models whose specificity is good but sensitivity/True Positive Rate/Recall is not good. If the Model objective is to find the customers who will not churn, then Specifity can be considered.
- Final Model and metrics on test set: We recommend the model 'Logistic Regression with RFE' for telecom churn prediction with an overall accuracy of 0.83 and a Sensitivity/Recall/True Positive Rate of 0.799. Looking at the specificity metric, which determines customers who will not churn is also good at 0.83.

## Technologies Used
- Python - 3.8
- Matplotlib - 3.7.1
- NumPy - 1.23.4

## Contact
Created by [https://github.com/udaykiranpujaari72] - feel free to contact me!
