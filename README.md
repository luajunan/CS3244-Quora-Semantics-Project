# CS3244-45-Quora-Semantics-Project

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

## Team Contributers:
1. Jeremy Lee
2. Lee Penn Han
3. Loke Kay Chi
4. Lua Jun An
5. Neaton Ang
6. Swa Yong Shen

## Mentor: 
1. Cheong Siu Hong

## Referenced Work:
1. https://keras.io/api/
2. https://towardsdatascience.com/quora-question-pairs-similarity-tackling-a-real-life-nlp-problem-ab55c5da2e84
3. https://towardsdatascience.com/dont-overfit-how-to-prevent-overfitting-in-your-deep-learning-models-63274e552323
4. https://machinelearningmastery.com/diagnose-overfitting-underfitting-lstm-models/ https://github.com/bradleypallen/keras-quora-question-pairs
5. https://blog.mlreview.com/implementing-malstm-on-kaggles-quora-question-pairs-competition-8b31b0b16a07
6. https://github.com/MikeXydas/SiameseLSTM
7. https://stackabuse.com/python-for-nlp-creating-multi-data-type-classification-models-with-keras/#creatingamodelwithmultipleinputs
8. https://mlwhiz.com/blog/2019/02/08/deeplearning_nlp_conventional_methods/ https://machinelearningmastery.com/avoid-overfitting-by-early-stopping-with-xgboost-in-python/
9. https://kevinvecmanis.io/machine%20learning/hyperparameter%20tuning/dataviz/python/2019/05/11/XGBoost-Tuning-Visual-Guide.html
10. https://blog.cambridgespark.com/hyperparameter-tuning-in-xgboost-4ff9100a3b2f
11. https://towardsdatascience.com/fine-tuning-xgboost-in-python-like-a-boss-b4543ed8b1e
12. https://towardsdatascience.com/xgboost-fine-tune-and-optimize-your-model-23d996fab663
13. https://www.vebuso.com/2020/03/svm-hyperparameter-tuning-using-gridsearchcv/
14. https://towardsdatascience.com/an-implementation-and-explanation-of-the-random-forest-in-python-77bf308a9b76
15. https://www.vox.com/recode/2019/5/16/18627157/quora-value-billion-question-answer 
16. https://www.vox.com/recode/2019/5/16/18627157/quora-value-billion-question-answer 
17. https://stackoverflow.blog/2019/01/18/state-of-the-stack-2019-a-year-in-review/ 
18. https://www.theverge.com/2020/12/1/21754984/reddit-dau-daily-users-revealed
19. https://www.kaggle.com/c/quora-question-pairs/discussion/34355
20. https://arxiv.org/abs/1606.01933
21. https://github.com/ashwin4glory/Quora-Question-Pair-Similarity/blob/master/4.ML_models.ipynb
22. https://blog.mlreview.com/implementing-malstm-on-kaggles-quora-question-pairs-competition-8b31b0b16a07
23. https://arxiv.org/abs/1908.10084
24. https://towardsdatascience.com/boosting-in-machine-learning-and-the-implementation-of-xgboost-in-python-fb5365e9f2a0       
