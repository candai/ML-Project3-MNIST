# ML-Project3-MNIST

Dataset Chosen for this project: MNIST Dataset (https://www.kaggle.com/competitions/digit-recognizer/data)

In this project, I will try to develop a classifier that can most accurately identify digits in the MNIST dataset. In order to find the best model, I will try to develop and evaluate various models such as SVC, Random Forest, KNN and GaussianNB, and make use of hyperparamater optimization using grid search and PCA to optimize model performances. Hyperparamter Tuning, PCA and Kernel Selection techniques are used to enhance the model performances.

Using an SVC (C=10, gamma=0.01) with a model kernel of 'rbf', PCA(n_components=50), and a MinMaxScaler, model proved to be the best performing in terms of f1 score. The evaluation report above shows that the test accuracy is 97.8857% and the validation accuracy is 0.9810.

The confusion matrix shows that the highest misclassification is with number 3 being mislabeled as 2 and number 9 being mislabeled as 4, with both 23 misclassifications. Overall, the testing and validation accuracies are quite high both close to 98 %. Using hyperparameter tuning, PCA and GridSearch, the best model was developed and tested.
