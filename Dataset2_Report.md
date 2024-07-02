Feature Selection is one of the core concepts in machine learning which hugely impacts the performance of your model. The data features that you use to train your machine learning models have a huge influence on the performance you can achieve.

Irrelevant or partially relevant features can negatively impact model performance.

### Feature Importance
You can get the feature importance of each feature of your dataset by using the feature importance property of the model.

Feature importance gives you a score for each feature of your data, the higher the score more important or relevant is the feature towards your output variable.

Feature importance is an inbuilt class that comes with Tree Based Classifiers, we will be using Extra Tree Classifier for extracting the top 10 features for the dataset.

### Model Performance Comparison
For a decision tree classifier, we observed an accuracy score of ~0.80 using all the features; but using only the top 10 most impactful features, we observed an increase in accuarcy of 0.85, showing that the features do indeed have a higher correlation to the target and feature selection positively impacted our classification model.