# Customer-Churn-Prediction-with-an-Artificial-Neural-Network-ANN-
This project aims to build a machine learning model, based on an Artificial Neural Network (ANN), that predicts the likelihood of a bank customer leaving the institution. Customer churn prediction is critical for businesses looking to retain clients and minimize revenue loss.

### Context and Objectives
The dataset used contains various customer details, including demographic data (age, gender, country), financial characteristics (credit score, balance, estimated salary), and behavioral information (tenure, number of products owned, active member status). The goal is to predict the `Exited` column, indicating whether a customer has left the bank (1) or remained (0).

### Key Steps
1. **Data Preparation**: 
   - Cleaning and transforming the dataset, encoding categorical variables (such as `Geography` and `Gender`), and normalizing values to enhance model convergence.

2. **ANN Model Construction**:
   - Building an Artificial Neural Network model using TensorFlow and Keras. The model includes hidden layers with non-linear activation to capture complex relationships in the data.

3. **Training and Evaluation**:
   - Training the model on a subset of the data and evaluating its performance on a test set using metrics such as accuracy, recall, and F1-score to gauge its generalization capabilities.

4. **Results Interpretation**:
   - Analyzing model performance to identify key factors influencing churn, helping the bank take proactive measures to retain at-risk clients.

### Importance and Applications
This project demonstrates how deep learning models can be applied in the banking sector to anticipate customer behavior and improve retention strategies. By understanding the factors associated with churn, banks can reduce customer attrition while enhancing satisfaction and engagement.

This notebook serves as a practical guide for building churn prediction models and offers valuable insights for data analysts and machine learning practitioners interested in neural network applications within financial services.
