# AirQualityBeijing

I trained the following 3 models in order to predict pm2.5 (particulate matter) values and checked the model performance with k-fold cross-validation. 
* Artificial Neural Network, generated with tensorflow (210123_kfold_AirQual_ANN.ipynb) --> Mean Squared Error: 3778.259; Standard Deviation: 195.038
* Random Forest Regressor (210123_kfold_AirQual_RandomForest.ipynb) --> Mean Squared Error: 2293.779; Standard Deviation: 135.446
* Decision Tree Regressor (210123_kfold_AirQual_DecisionTree.ipynb) --> Mean Squared Error: 4327.621; Standard Deviation: 352.371

### Based on the validation results, the random forest regressor shows the best performance, followed by the artificial neural network and the decision tree regressor.

Dataset is uploaded and taken from UCI Machine Learning Repository (Liang, X., Zou, T., Guo, B., Li, S., Zhang, H., Zhang, S., Huang, H. and Chen, S. X. (2015). Assessing Beijing'sPM2.5 pollution: severity, weather impact, APEC and winter heating. Proceedings of the Royal Society A, 471,20150257.)
