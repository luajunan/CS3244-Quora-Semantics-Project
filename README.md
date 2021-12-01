# CS3244 Project Title: Quora Question Pairs

## Project Description

The motivation behind this project is to reduce question duplicates on knowledge-sharing platforms like [Stackoverflow](https://stackoverflow.com/), [Google](https://google.com), [Quora](https://www.quora.com/) and [Reddit](https://www.reddit.com/).

Duplicate questions negatively affects user experience as discussion for the same question is segmented into different posts. Hence, the aim of our project is to **minimise the duplicates (False Positive)** instances within the dataset.

Machine Learning Techniques:
1. Exploratory Data Analysis
2. Feature Engineering
3. Support Vector Machine
4. Logistic Regression
5. Random Forest Classifier
6. XGBoost
7. Recurrent Neural Networks (RNN)
8. Siamese Recurrent Neural Networks (Siamese RNN)
9. Natural Language Processing (NLP)

## Evaluation of Models
| **Models** | **F1** | **Recall** | **Precision** | **Accuracy** |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| SVM | 69.0%  | 90.3%  | 55.9%  | 70.2%  |
| Logistic Regression | 53.6%  | 50.0%  | 57.6%  | 68.0%  |
| RFC | 66.0%  | 76.0%  | 58.0%  | 71.0%  |
| XGBoost | 70.8%  | 86.7%  | 59.7%  | 73.7%  |
| RNN | 77.0% | 78.1%  | 75.9%  | 82.8% |
| Siamese RNN | 77.0% (+0.034) | 78.1% (+0.061)  | 75.9% (+0.008)  | 82.8% (+0.019) |

## Final Siamese RNN Architecture
<img width="1154" alt="Screenshot 2021-12-01 at 10 48 08 PM" src="https://user-images.githubusercontent.com/65394783/144255954-3db8717c-71ec-453d-8608-96c01cd16f2a.png">

## Final Model
Even though the improvements were minor, we regarded it as significant due to the large dataset it was trained over (~400,000 rows). Hence, the final model chosen was the **Siamese Recurrent Neural Networks with Engineered Features.**

## Team Contributers:
1. Jeremy Lee
2. [Lee Penn Han](https://github.com/pennhanlee)
3. [Loke Kay Chi](https://github.com/kaychiiiii)
4. [Lua Jun An](https://github.com/luajunan)
5. [Neaton Ang](https://github.com/neatonang)
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
