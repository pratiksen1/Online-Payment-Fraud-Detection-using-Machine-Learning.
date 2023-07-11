To identify online fraud with machine learning, we need to train a machine learning model for classifying dradulent and non-fradulent payments.
Collected a dataset from Kaggle.
columns from the dataset steps: represnts a unit of time where 1 step equals 1 hour
type: type of online transaction. PAYMENT, CASH_OUT, TRANSFER 
amount: the amount of the transaction. 
nameOrig: customer starting the transaction(C1231006815).
oldbalanceOrig: balance before the transaction.
newbalanceOrig: balance after the transaction.
nameDest: recipient of the transaction(M1979787155).
oldbalanceDest: initial balance of recipient before the transaction.
newbalanceDest: the new balance of recipient after the transaction 
isFraud: Fraud Transaction
