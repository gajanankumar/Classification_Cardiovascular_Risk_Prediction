# Classification_Cardiovascular_Risk_Prediction

* To build the models, missing values were handled, feature engineering and feature selection was performed, and the training dataset was oversampled using SMOTE to reduce bias on one outcome.
* Recall was chosen as the model evaluation metric because it was very important that we reduce the false negatives.
* Initial set of predictions were obtained using the baseline model,logistic regression model, and other commonly used classification models were also build in search of better predictions.
* It is critical that the model we develop has a high recall score. It is OK if the model incorrectly identifies a healthy patient as a high risk patient because it will not result in death, but if a high risk patient is incorrectly labelled as healthy, it may result in fatality.
* Future developments must include a strategy to improve the model recall score, enabling us to save even more lives from this disease. This includes involving more people in the study, and include people with different medical history, etc build an application with better recall score.
* Using SHAP we identified the feature importances and identified that, gender, education and age were 3 main influencers.

* Other methods or models could be used to further improve the model. With the help of a medical expert we could engineer more features which would in turn help improve the model further.
* 7 models were used in the project, namely, Logistic Regression,Decision Tree, Random Forest, XGB Classifier, Naive bayes classifier,KNN and SVM. XGBoost was best performing base model as it did not overfit as much as the Random Forest. Hyperparameter tuning was done on the same model.

* The final results of the model are almost close to the base model and we have acheived almost 87% test accuracy and 89% test precision, where as we have acheived almost 84% test recall. We will be mainly focus on recall as the aim is to have less false negatives.
