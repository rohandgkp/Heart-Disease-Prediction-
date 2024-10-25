# Heart-Disease-Prediction-
The experiment was conducted in 2 phases - Without feature selection and with feature selection techniques.
The CSV dataset consists of 1100 rows approximately, divided into 2 parts - training (80%) and testing (20%).
In the first phase, 20 existing Machine Learning and Deep Learning were employed, namely, Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, Support Vector Machine, Gaussian Naive Bayes, Extreme Gradient Boosting, Adaptive Boosting, Stochastic Gradient Descent, Gradient Boosting Machine, Extra Tree Classifier, Categorical Boosting, Light Gradient Boosting Machine, Multi-Layered Perceptron, Recurrent Neural Network (RNN), Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), Bidirectional LSTM, Bidirectional GRU, Convolutional Neural Network (CNN).
In addition to these 20 models, a hybrid model was built using RNN, LSTM, GRU, Bi-LSTM, Bi-GRU, and CNN.
The training was done over 100 epochs, with an early stopping of 15 epochs.
In the second phase, 11 feature selection were applied to the original dataset, namely, Information Gain, Chi-Square Test, Fisher's Discriminant Analysis, Variance Threshold, Mean Absolute Difference, Dispersion Ratio, Relief, Lasso, Random Forest Importance, Linear Discriminant Analysis, and Principal Component Analysis.
The dataset was divided into training (80%) and testing (20%) sets.
The 21 classifiers were then trained on the dataset.
Extreme Gradient Boosting without feature selection outperformed the other classifiers, by achieving 97.5% testing accuracy.
