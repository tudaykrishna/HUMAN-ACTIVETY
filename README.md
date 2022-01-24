# Human-Activity-Recognition-by-using-SVM

Recognize 6 human activities, like: standing, walking, lying, sitting, walking upstairs, walking downstairs
The dataset is from UCI Machine Learning repository: 

http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions?ref=datanews.io


This project firstly preprocess data, then use PCA to reduct dimention from 561 to 200, then use 8-fold cross validation to choose a better parameter for SVM model.
The final accuracy is up to 95%
