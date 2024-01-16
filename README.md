# Titanic-Survival-Predicition
Unlocking Titanic’s Secrets: Predicting Survival with Logistic Regression using Pyspark

## Introduction:

In the realm of data science, predictive analytics serves as the driving force behind many impactful applications. Among the myriad of techniques at our disposal, logistic regression stands out as a powerful tool for solving classification problems. In this blog post, we will delve into the fascinating world of logistic regression and explore a real-world project that showcases its efficacy in action.

## Project Overview:

For our logistic regression project, we set out to tackle a pressing challenge in the Titanic Dataset — predicting how many people survived. Dataset contains various data of the passangers like Name, Age, Sex, Ticket, Fare and various other fields. Let’s dive into the Project and we will be using Pyspark for this.

## Feature Engineering:

With a clear grasp of the data, we dived into feature engineering — a crucial step in preparing our dataset for logistic regression. We performed various transformations, including one-hot encoding for categorical variables, scaling numerical features, and handling missing values. Additionally, we explored interactions and derived new features that might capture complex relationships within the data.

## Model Building and Training:

Equipped with a well-prepared dataset, we proceeded to construct our logistic regression model. We split the data into training and testing sets, using cross-validation techniques to optimize hyperparameters and prevent overfitting. We fit our model to the training data and fine-tuned it using techniques like regularization and feature selection to enhance performance.

## Conclusion:

Logistic regression is a powerful technique in the field of predictive analytics, especially for solving classification problems. Its interpretability and ability to handle both numerical and categorical features make it a valuable tool for extracting insights and making predictions.

Throughout our logistic regression project, we embarked on a journey of data exploration, feature engineering, model building, and evaluation. By leveraging PySpark’s feature engineering modules such as VectorAssembler, StringIndexer, OneHotEncoder, and VectorIndexer, we were able to preprocess and transform our data effectively.

The Pipeline module in PySpark played a crucial role in organizing and executing the different stages of our project. It allowed us to create a streamlined workflow by encapsulating data transformations and machine learning algorithms into a single pipeline. This not only enhanced efficiency but also facilitated the reusability of the pipeline on new data.

By evaluating our logistic regression model’s performance using metrics such as accuracy, precision, recall, F1 score, and AUC, we were able to assess its predictive power. A higher AUC value indicates better performance, as it signifies the model’s ability to discriminate between different classes accurately.

Moreover, logistic regression’s interpretability allowed us to derive meaningful insights from the model’s coefficient values. These insights guided us in identifying the most influential features driving customer churn, enabling us to propose targeted retention strategies for the e-commerce company.

Overall, our logistic regression project showcased the effectiveness of this technique in solving classification problems. Through careful data preprocessing, feature engineering, and model evaluation, we harnessed the power of logistic regression to extract valuable insights and make accurate predictions. By leveraging PySpark’s capabilities, we were able to handle large-scale data and streamline our workflow, further enhancing the efficiency and effectiveness of our project.

Happy to connect over YB’s [LinkedIn](https://www.linkedin.com/in/yash-bhairao/)
