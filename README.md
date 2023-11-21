# Flight-delay-prediction
A two-stage predictive machine learning engine that forecasts the on-time performance of flights in the USA based on data collected between 2016 and 2017.

# Results
The flight and weather data were combined into a single data set and pre-processed . A class imbalance was detected in the data, due to which there waws a bias towards the 'Not Delayed' class. The imbalace was handled using SMOTE and random undersampling, out of which SMOTE showcased better results. Out of all the classifiers, Random forest classifier performed the best. Extra Trees regressor was pipe-lined. 

