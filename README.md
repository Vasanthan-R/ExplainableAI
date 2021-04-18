## Use-case based Interpretation of Machine Learning Models using Explainable AI

This project focuses on two use cases namely: 1. Customer Review Score Detection (the SAP Labs hackathon dataset) 2. An extra use-case: Credit Card Fraudulent Detection - https://www.kaggle.com/mlg-ulb/creditcardfraud

We make use of explainable AI to generate both global and local explanations for these use cases and evaluate/benchmark these explanation using various metrics. The generated explanations are in natural language and are understandable by business users.

The Customer Review dataset consists of textual and numerical fields whereas the Credit Card dataset contain only numerical fields.

The XAI framework explains the classification by the following models : Linear SVC and LSTM.

Text embedding techniques such as TF-IDF and Bag of Words are used to handle textual data. 
