# Telecom Opereator Client Churn Forecast
Interconnect, a telecom operator would like to forecast their churn of clients. If it’s discovered that a user is planning to leave, they will be offered promotional codes and special plan options. Their clientele’s personal data, along with their plans and contracts is used to train a model that will predict whether a client will leave or not. To do this project, all data is combined together first, then preprocessed to ensure its valid and usable for training a model. Various classification algorithms such as Decision Tree Classifier, CatBoost Classifier, and LightGBM Classifier were used.

To Run
Clone the project
```
git clone https://github.com/filzamazahir/ClientChurnForecast.git
```

Make sure to have pandas, numpy, scikit-learn, and matplotlib libraries installed.

Run telecomclientchurnforecast.ipynb

## Results
Exploratory Data Analysis showed that the clients who were active were paying more monthly compared to those who left. Various classification algorithms such as Decision Tree Classifier, Random Forest Classifier, CatBoost Classifier, LightGBM Classifier and Gradient Boosting Classifier were used to train models to pick the best one. The final model selected was a LightGBM Classifier, testing was done on the test set which gave a AUC-ROC score of 0.83, and an accuracy score of 0.79. It passed our threshold of AUC-ROC score of 0.75.
