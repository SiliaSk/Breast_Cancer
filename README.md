# Classification-Breast-Cancer
After working with linear regression, I wanted to explore machine learning further and developed a classification model to predict whether a breast tumor was benign or malignant.

# Building the model 
Firstly, I imported the dataset and defined my data frame as usual. In this case, it was necessary to normalize the features in X (scaling) to ensure that all variables were on the same scale, thereby improving the performance and stability of the model.

Next, I split the data into training and test sets using an 80-20 ratio, with 80% for training and 20% for testing, in order to ensure proper evaluation of the model's performance. I trained the model using Logistic Regression and evaluated its performance on the testing set. Then, I evaluated the accuracy to assess the effectiveness of the model, which, fortunately, was sufficiently high.


Finally, I displayed a confusion matrix with a heatmap to better understand the model's accuracy and performance, highlighting true positives, true negatives, false positives, and false negatives across classes.

