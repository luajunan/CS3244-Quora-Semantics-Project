#Source Codes

List of Source Code: 
1. Feature Engineering
- Source code containing feature engineering of raw question pairs from the Quora Dataset
2. Recurrent Neural Network
- Source code containing exploration into RNN as a solution
3. Recurrent Neural Network Mass Testing
- Source code containing several experiments with parameter tuning and different flavours
of RNN including Bidirectional, Multiple Dense Layers and inclusion of Engineered
Features 
5. SVM
- Source code containing exploration into SVM as a model to estimate baseline performance.
6. RFC
- Source code containing exploration in RFC as a baseline model for further experiment
and comparison of future models 
7. Logistic Regression
- Source code containing exploration in logistic regression as a baseline model 
8. XGBoost
- Source code containing exploration of XGBoost model, together with new word embedding feature
9. Model Explanation
- Source code containing investigation on wrongly predicted instances

Note: 
1. Due to the large file sizes of the engineered features csv file and GloVe word embedding, they are not included together with the required source codes. 
2. The engineered features csv file can be obtained by running the Quora Pair train dataset from [Kaggle](https://www.kaggle.com/c/quora-question-pairs/data) in the Feature Engineering ipynb file.
3. The `glove.840b.300d.zip` file can be obtained through this [link](https://nlp.stanford.edu/projects/glove/).
