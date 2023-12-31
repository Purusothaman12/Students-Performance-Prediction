# Students-Performance-Prediction
The main goal of this machine learning project is to develop a logistic regression model to predict a student's college grades as high, medium and low.

Given that the study should not be false positive, the focus is on improving the precision of the model. Preciion is an indicator of the performance of a machine learning model, that is, how well the model predicts. Precision is the number of true positives divided by the total number of predicted positives.

To address the issue of imbalanced dataset, where the number of medium class may be significantly larger than high and low class, resampling techniques can be employed. Resampling involves either oversampling the minority class (low and high) or undersampling the majority class (medium class) to create a balanced dataset. This helps to mitigate the impact of class imbalance on model performance.

Cross Validation is employed to iteratively evaluate the performance of the model on different subsets of the data, ensuring robustness and generalizability.

By implementing these techniques, we aim to develop a logistic regression model that effectively predicts performance of students, with a particular emphasis on improving the precision score
