# Predictive ML Model 

## Overview 

Understanding and resolving customer complaints is crucial for improving customer satisfaction and boosting sales. By analyzing consumer complaint data, companies can better predict potential disputes and take proactive measures to address them. This project focuses on using machine learning to classify customer complaints and predict whether a customer dispute will occur.
* Utilize Python libraries to manipulate and explore the dataset.
* Pandas: For data manipulation and operations.
* Seaborn and Matplotlib: For data visualization and exploratory data analysis (EDA).
* Sklearn: For building machine learning models and visualizing their performance.

## Business Understanding

Effective complaint analysis & resolution is critical for maintaining customer satisfaction and enhancing sales growth. Understanding and predicting whether a customer complaint will be disputed allows businesses to take proactive measures to address issues, thereby improving customer retention and satisfaction. This analysis is particularly relevant for companies aiming to enhance their customer service and support systems.

## Data Understanding

The data was sourced from consumer complaint records, comprising approximately 358,810 training entries and 119,606 test entries.The dataset consists of customer complaints and related information:

* Dispute: Target variable indicating if there is a dispute with the company.
* Date received: Date the complaint was received.
* Product: Types of products offered by the company (e.g., credit cards, debit cards, transaction methods, accounts, locker services, money-related products).
* Sub-product: Specifics within a product category (e.g., loans, insurance, mortgages).
* Issue: Description of the customer's complaint.
* Company public response: Company's response to the complaint.
* Company: Name of the company involved.
* State: State of residence of the customer 
* ZIP code: ZIP code

## Modeling and Evaluation

Several classification algorithms were employed, including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. The final model, a Random Forest classifier, demonstrated superior performance with high accuracy and precision in predicting disputed complaints. Feature importance analysis revealed that factors such as the duration and type of issue significantly influenced the likelihood of a dispute.

## Conclusion

The model provides valuable insights into the factors that lead to customer disputes, enabling companies to enhance their complaint resolution processes. Future work may include incorporating more detailed customer behavior data and exploring additional machine learning techniques to further improve prediction accuracy
