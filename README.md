

# IBM Attrition

For this notebook, I use the IMB Attrition dataset (available on Kaggle) to do the following:
* Compare the predictive performance of Logistic Regression, Random Forest, and XGBoost models using Confusions Matrices and ROC Curves 
* Explore relative feature importance with respect to employee attrition for the XGBoost model using Gini Importances and Permutation_Importance
* Further explore feature importance through visualization tools PDP Plots, PDP Interaction Plots, and Shapley Waterfall Plots
* Use insights from the feature importances to perform dimensionality reduction
* Rerun models on smaller feature matrix

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Insights

* The three models performed similarly on the original feature matrix, with the XGBoost slightly edging out the others
* Some important features included 'OverTime', 'NumberofCompaniesWorked', and 'BusinessTravel'
* After simplifying the model by reducing dimensionality, the simple Logistic Regression outperformed the others, which suffered from overfitting to the training data


