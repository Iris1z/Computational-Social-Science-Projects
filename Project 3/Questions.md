**Data Preprocessing**
Data Preprocessing has always be a big problem for me. I have difficulties in dropping features (further explained below) and scaling data. For instance, I debated whether scaling was necessary and eventually decided not to apply it, as it seemed to negatively impact the performance of Logistic Regression and showed no improvement for Random Forest and XGBoost.

**Feature Selection**
In terms of feature selection, as i mentioned in *Project 3 Students.ipynb*, on the one hand, I am aware of the inherent feature selection capabilities embedded in algorithms of Random Forest and XGBoost, which naturally prioritize important features during training. On the other hand, I also acknowledge that Logic Regression has limited ability in this regard. Though I chose not to implement extra feature selection to ensure consistency across the training datasets for all models, I am concerned that this decision may negatively influence the performance of Logic Regression.

**Hyperparameter Tuning**
When dealing with a large dataset, hyperparameter tuning can be computationally expensive, and choosing cv definitely only increases this burden. Instead of randomly guessing and adjusting parameters in GridSearchCV, smarter methods are needed.

**Prof's Comments**
Great job overall. Well done with the visualizations, . "At least, during a cold winter, a heating computer makes things a bit easier! : )" --LOL. Love how you visually compared variable importance across models. Great model and feature importance interpretation. One small note is that balance on overall feature importance should not be a standout for a model--the question is whether the features really are of similar importance or not. So, this should not be the reason you chose RF over XGboost. Also, what was your findings of the predictive vs random auditing? For the test (2014) analysis--I think your missing an analysis of how well your model did on test data compared to training? I'm also interested in seeing that to determine if the model is overfitting. Great policy / Discussion answers.

Kasey Zapatka, Dec 10, 2024 at 4:14pm
