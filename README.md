# payment-Fraud-Detection

To combat online payment fraud, machine learning can be utilized as a tool for identifying fraudulent activity. This can be done by training a machine learning model to recognize patterns and anomalies in online payment transactions that indicate fraud. In order to train this model, a dataset containing information about past instances of online payment fraud is required and sourced from [Kaggle](https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection) and the dataset includes both fraudulent and non-fraudulent payments.

Dataset Columns.
| Columns          |        Meaning                                       |   
| --------------- |:-----------------------------------------------------:|
| step            |  represents a unit of time where 1 step equals 1 hour |
| type            |  type of online transaction                           |
| amount          |  the amount of the transaction                        |
| nameOrig        |  customer starting the transaction                    |
| oldbalanceOrg   |   balance before the transaction                      |
| newbalanceOrig  |  balance after the transaction                        |
| nameDest        |  recipient of the transaction                         |
| oldbalanceDest  |  initial balance of recipient before the transaction  |
| newbalanceDest  |  the new balance of recipient after the transaction   |
| isFraud         |  fraud transaction                                    |
| isFlaggedFraud  |  Fraud Transaction that was flagged                   |
