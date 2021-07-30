This project was completed during Yandex.Practicum Data Scientist professional program.

**Key words**: MachineLearning, SupervisedLearning, model, LogisticRegression, RandomForestClassifier, f1_score, OrdinalEncoder 

**Libraries used**: pandas, sklearn

## Project's goal<a id='goal'></a>

We work at Beta bank, which suffer from client outflow
We need to **predict** whether a **customer will leave the bank soon**. We have the data on **clients’ past behavior** and **termination of contracts** with the bank.  
Out task is to **build a model** with the **maximum possible F1 score**. Acceptable **F1 score** of at least **0.59** on the test set.

In this project I've build a model to predict clients churn:
 * Data was preprocessed
 * Used ordinal encoder for tree algoritms
 * Tested different approaches for eliminating class imbalances
 * Trained ML models such as - DecisionTreeClassifier, RandomForestClassifier, LogisticRegression
 * Managed to get required f1-score, which allows to predict clients behavior
