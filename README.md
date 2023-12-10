Diabetes Diagnosis Machine Learning Pipeline

This repository hosts a robust machine learning and data science pipeline specifically designed for the diagnosis of diabetes. Developed in Python, it features a range of models, including Logistic Regression with regularization, Random Forest, SVM, and XGBoost. These models have been meticulously trained and fine-tuned using a comprehensive dataset obtained from Kaggle.

The core components of the pipeline include:

1.	Random State Selection: Five distinct random states were chosen to ensure the reproducibility and robustness of the model's performance and to account for uncertainties due to splitting and non-deterministic ML methods.
2.	Data Splitting: The dataset was stratified and split into training (60%), validation (20%), and testing (20%) sets. This approach ensured a proportional representation of the target classes across each subset.
3.	Preprocessing: Standard scaling was applied to normalize the continuous variables, and one-hot encoding was used to convert categorical variables into a format suitable for model training.
4.	Hyperparameter Tuning: An exhaustive grid search was conducted across various hyperparameter combinations to identify the configuration that best performs the validation set.
5.	Model Evaluation: Finalize the optimal model based on grid search results and evaluate its effectiveness on the previously unseen test set to assess its generalization capability.


This project has been structured to cater to both technical and non-technical audiences, with the findings and methodologies comprehensively documented in an accessible report and presentation stored in the folder 'Report.' The primary aim is to leverage advanced machine learning techniques to aid in the early and accurate diagnosis of diabetes, thereby contributing to better healthcare outcomes.
