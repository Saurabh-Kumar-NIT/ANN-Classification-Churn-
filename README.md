# ANN Classification Churn Prediction
## 1) Dataset Description
The dataset used for this project consists of customer information from a subscription-based service, containing various features that influence customer behavior. The dataset comprises the following key columns:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (e.g., Male, Female).
- **Age**: Age of the customer.
- **GeographicLocation**: The region where the customer resides.
- **SubscriptionType**: The type of subscription plan (e.g., Basic, Premium).
- **NumberOfLogins**: Total number of logins during the subscription period.
- **DurationOfUsage**: Average duration of service usage per session (in minutes).
- **Churn**: Target variable indicating whether the customer has churned (1) or not (0).



### 2) Problem Statement
In today’s competitive marketplace, retaining customers is as important as acquiring new ones. The primary objective of this project is to predict customer churn for a subscription-based service using an Artificial Neural Network (ANN). Understanding which customers are likely to churn allows businesses to take proactive measures to retain them, ultimately reducing revenue loss.

Customer churn not only affects the bottom line but also incurs higher costs in acquiring new customers to replace those who leave. By predicting churn accurately, businesses can target at-risk customers with tailored retention strategies.

#### 3) Objective
The main objectives of this project are as follows:

Data Analysis: Conduct a thorough analysis of the dataset to uncover insights and patterns that contribute to customer churn.
Model Development: Build an ANN model to predict churn based on the features in the dataset. The model will be trained to recognize the patterns that lead to customer attrition.
Performance Evaluation: Assess the model's accuracy and effectiveness using appropriate metrics, ensuring that it generalizes well to new, unseen data.

##### 4) Motivation
The motivation behind this project stems from the critical importance of customer retention in subscription-based business models. High churn rates can devastate a company’s revenue and market position. By leveraging machine learning techniques, businesses can gain valuable insights into customer behavior and develop effective strategies for retention.

Investing in churn prediction not only minimizes revenue loss but also enhances customer satisfaction by allowing businesses to address issues before they lead to churn. This proactive approach fosters customer loyalty and increases overall profitability.

##### 5) Project Gap
While there are numerous existing customer churn prediction models, many of these rely on traditional machine learning methods that may not fully capture the complexities of customer behavior. This project aims to address this gap by implementing an Artificial Neural Network, which has the potential to uncover intricate relationships within the data that simpler models might miss.

By utilizing an ANN, we aim to improve prediction accuracy, providing businesses with a more powerful tool for understanding and preventing customer churn.

## 6) Conclusion and Insights
After developing and training the ANN model, we achieved a training accuracy of approximately 87.15% and a validation accuracy of 85.75%. These metrics indicate that the model effectively learns from the training data and can generalize to new instances.

Key insights from the analysis highlighted that certain features, such as SubscriptionType, NumberOfLogins, and DurationOfUsage, significantly impact the likelihood of churn. For instance, customers on Basic plans demonstrated a higher churn rate compared to those on Premium plans, suggesting that enhancing the value proposition for Basic plan subscribers could improve retention.

By understanding these insights, businesses can tailor their retention strategies to focus on high-risk segments, thereby enhancing customer satisfaction and reducing churn.

## 7)Metrics
Training Accuracy: 87.15%
Validation Accuracy: 85.75%
Loss Function: Binary Cross-Entropy, used for measuring the model’s performance on binary classification tasks.
Optimizer: Adam, chosen for its efficiency in training deep learning models.
Epochs: 100, indicating the number of complete passes through the training dataset.

## 8)Future Work
Feature Engineering: Adding more features that may impact churn, such as customer feedback and service complaints.
Hyperparameter Tuning: Experimenting with different network architectures and hyperparameters to optimize model performance.
Comparative Analysis: Evaluating other machine learning algorithms against the ANN model to identify the best approach for churn prediction.
By continuously refining the model and incorporating new data, businesses can stay ahead in retaining valuable customers and maintaining a competitive edge in the market.
