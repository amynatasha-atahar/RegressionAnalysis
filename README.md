# Regression Analysis
The aim of the project is to compare four types of regression models in predicting factors that influence total bikes rented. 

# Discussion and Recommendation
* K-Neighbors Regressor has the lowest error compared to other algorithms (Linear Regression, Random Forest Regressor, Support Vector Regressor).
* All the classifiers RMSLE result were decreased because it was tuning by the optimum parameter to improve models accuracy except Random Forest which was slightly increased may be due to hyper-parameter tuning used.
* Use TuneRF before applying Random Forest algorithm to improve its performance in predicting factors that influence the total number of bikes rented (Patil et. al., 2015). 

# Conclusion
The best performance of the algorithm for this project is **K-Neighbors Regressor (KNR)** where the value of RMSLE is the lowest compared to other algorithms.

# Reference
* Patil, A., Musale, K. & Rao, B. P. (2015). Bike sharing demand prediction using randomforests. International Journal of Innovative Science, Engineering and Technology, 2 (4): 1218 – 1223.
