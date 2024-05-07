This project aims to predict the airway pressure which is a time series regression problem according to the given dataset. 
After data preprocessing, recurrent neural network (RNN) is used to solve the problem.
To experiment whether classical machine learning algorithm can outperform RNN, various types of machine learning algorthim including Linear Regression, K-Nearest Neigbor and Decision Tree are implemented using the sklearn library to solve the problem.
Since Decision Tree has the best performance among the others, tree-based ensemble machine learning algorithm including Random Forest, XGBoost and CatBoost are implemented. 
The results show that Random Forest and XGBoost had outperform the RNN in this particular project. 
