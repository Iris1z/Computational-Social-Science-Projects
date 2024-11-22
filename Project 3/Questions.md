**Data Preprocessing**
Data Preprocessing has always be a big problem for me. I have difficulties in dropping features (further explained below) and scaling data. For instance, I debated whether scaling was necessary and eventually decided not to apply it, as it seemed to negatively impact the performance of Logistic Regression and showed no improvement for Random Forest and XGBoost.

**Feature Selection**
In terms of feature selection, as i mentioned in *Project 3 Students.ipynb*, on the one hand, I am aware of the inherent feature selection capabilities embedded in algorithms of Random Forest and XGBoost, which naturally prioritize important features during training. On the other hand, I also acknowledge that Logic Regression has limited ability in this regard. Though I chose not to implement extra feature selection to ensure consistency across the training datasets for all models, I am concerned that this decision may negatively influence the performance of Logic Regression.

**Hyperparameter Tuning**
When dealing with a large dataset, hyperparameter tuning can be computationally expensive, and choosing cv definitely only increases this burden. Instead of randomly guessing and adjusting parameters in GridSearchCV, smarter methods are needed.

