# Wisconsin-Breast-Cancer-Learning-Excercise

Here I have attempted to perform basic binary classification of breast cancer cells based on data collected by UCI, provided 
at: https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/

The data contains  data about 458 Benign cells and 241 Malignant cells describing the diagnosis, area, perimeter etc of the cells. 

In my solution I have described:
    1. The mean, median and standard deviation of the 'perimeter' feature. 
    2. Analyse if the 'radius' feature is normally distributed or not.
    3. Train an SVM and Logistic Regression model by selecting appropriate features based on analysis of
       a heat map and scatter matrix. 
       The trained models have produced: 96.66% accuracy for SVM & 89.28% accuracy for Logistic Regression.
       
       


** Note: Due to a bug in the Pandas scatter_matrix() the scatter matrix plot shows up every few runs and then vanishes producing 
an incomplete looking plot.

Another bug is present in numpy which prevented me from performing cross-validation on my data. Cross-validation allows us to validate if the results 
produced by our models are actually correct or not. 
