This project was completed during Yandex.Practicum Data Scientist professional program.

**Key words**: MachineLearning, SupervisedLearning, model, LinearRegression, RandomForestRegressor, GradientBoostingClassifier, GridSearchCV 

**Libraries used**: pandas, numpy, plotly, matplotlib, cufflinks, sklearn

## Project's goal<a id='goal'></a>

Our goal is to prepare **prototype of a machine learning model** for the gold mining company. This company develops efficiency solutions for heavy industry.
The model should **predict the amount of gold recovered from gold ore**. We have the data on extraction and purification. The model will help to optimize the production and eliminate unprofitable parameters.
The metric for the task - sMape.
It is similar to MAE, but is expressed in relative values instead of absolute ones. It equally takes into account the scale of both the target and the prediction.

In this project I've build a model to predict the amount of gold recovered from gold ore:
 * Data was preprocessed
 * Explored the process and stages of gold extraction from the gold genus
 * Analyzed concentration of metals in gold ore
 * Developed funtcion for new metric - sMape
 * For tuninig hyperparametrs was used GridSearch 
 * Trained ML models such as - LinearRegression, RandomForestRegressor, DecisionTreeRegressor
 * Managed to get better sMape score than baseline models based on median target
