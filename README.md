# ML-intelligibility

The different parts of the project: 

five models are created for predicting house prices (the data from the kaggle competition is used)

Testing different ensembling methods to achieve the best results

the uncertainty of the model is quantified and different jacknife implementation are compared (the same steps are followed as the correpondant paper)

A new data of customers' likelihood to respond to an insurance contract proposition is used and pandas_profiling is tried to interprete the data and the variable. 

The impact of the variable on the classification problem is evaluated through Partial Dependance Plots (PDP) and Individual Conditional Expectation Curves (ICE)

The function of feature importance employed by sklearn's random forest is implemented by hand starting by decision trees

Permutation importances is implemented by hand and compared with the equivalent functions imported as such: "from eli5.sklearn.permutation_importance import PermutationImportance". This method is universal and doesn't depend on the ML algorithm used, however it demands a lot of ressources. 

SHappley Additive exPlaination (SHAP) is computed for the Random forest, SHARP indicates if the variables impacts positively or negatively the prediction. 



