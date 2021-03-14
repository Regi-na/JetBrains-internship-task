# JetBrains-internship-task
***
Prediction of five-year citation.  It was done in order to participate in JetBrains Internship 2021.
### INSTALLATION

```python
pip install numpy
pip install pandas
pip install seaborn
pip install xgboost
pip install matplotlib
pip install sklearn
pip install catboost
```
### Metric
R2 score, or the coefficient of determination was used to compare machine learning algorithms, which was calculated as follows: 

![image](https://user-images.githubusercontent.com/64543329/111061934-e375e200-84b6-11eb-90f1-54438043b686.png)

[The source](https://scikit-learn.org/stable/modules/model_evaluation.html#r2-score)

### Methods and results:
|Method | R2 with all features, ±0.2 | R2 with selected features, ±0.2 
---|---|---
|Linear Regression | 0.44 | 0.46
|Gradient Boosting Regressor |0.64 |0.74
|Decision Tree Regressor |0.28|0.56
|Random Forest Regressor |0.57|0.72
|AdaBoost Regressor |0.55|0.63
|XGB Regressor | 0.70|0.74
|CatBoost Regressor |0.69|0.75
