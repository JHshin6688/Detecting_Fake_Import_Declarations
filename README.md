# Detecting Fake Import Declarations
The goal of this project is to detect fake import declarations from the import declaration dataset provided by Korea Customs Service.

I implemented a machine learning model that predicts fake import declarations based on import documents.

In the 'feature_importance.ipynb', I found the importance of every feature by using random forest library.

In the 'randomized_trials.ipynb', I compared the performance of several models that are based on kneighborsClassifier, using different combination of features.

My final model achieved 92.946% prediction accuracy.
