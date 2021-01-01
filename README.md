# Covid-19 with Random Forest Model

Random Forest is an ensemble of Decision Trees. With a few exceptions, a RandomForestClassifier has all the hyperparameters of a DecisionTreeClassifier (to control 

how trees are grown), plus all the hyperparameters of a BaggingClassifier to control the ensemble itself.

An outbreak of COVID-19 started in December 2019 and at the time of the creation of this project was continuing to spread throughout the world. 

This case study was designed to drive home the important role that data science plays in real-world situations like this pandemic. This case study uses the Random 

Forest Classifier and a dataset from the South Korean cases of COVID-19 provided on Kaggle to encourage research on this important topic. The goal of the case study 

is to build a Random Forest Classifier to predict the 'state' of the patient.

1. First, needed packages and modules loaded into Python. 

2. Next, I loaded the data into a pandas dataframe for ease of use.

3. Handle Missing Values (with mean of the each column)

4. Check for duplicated rows

5. Split the data into test and train subsamples

6. Scale data to prep for model creation

7. Fit Random Forest Classifier

8. Create Confusion Matrix Plots

9. Conclusion 

Random Forest: Accuracy=0.860

Random Forest: f1-score=0.825

The popularity of random forest is primarily due to how well it performs in a multitude of data situations. It tends to handle highly correlated features well, 

where as a linear regression model would not. In this case study we demonstrate the performance ability even with only a few features and almost all of them 

being highly correlated with each other. Random Forest is also used as an efficient way to investigate the importance of a set of features with a large data set. 

Random forest is one of the first choices when building a decision tree, especially for multiclass classifications.





