# PyCaret-ClassificationModels-LoanApprovalPrediction-AnalyticsVidhyaHackathon

![p1](https://user-images.githubusercontent.com/65406908/88794182-0e036c80-d16c-11ea-8d78-c362f1f0369a.PNG)




Step 1: The data files used for this repository are stored with in this repository (train_loan.csv, test_loan.csv and sample_submission_loan.csv)

Step 2: The code to build Machine Learning Models is with in "PyCaret- Loan Approval Decision.ipynb" Notebook


# PyCaret was setup with several parameters

###### numeric_imputation= mean (Mean value is used to impute the missing values for numeric variables)

###### normalization= True (is a technique often applied as part of data preparation for machine learning. The goal of normalization is to rescale the values of numeric columns in the dataset without distorting differences in the ranges of values or losing information.)

###### transformation= True (Transformation is a more radical technique. Transformation changes the shape of the distribution such that the transformed data can be represented by a normal or approximate normal distribution)

###### feature_interaction= True (It is often seen in machine learning experiments when two features combined through an arithmetic operation becomes more significant in explaining variances in the data, than the same two features separately)

###### feature_selection= True (Feature Importance is a process used to select features in the dataset that contributes the most in predicting the target variable. Working with selected features instead of all the features reduces the risk of over-fitting, improves accuracy, and decreases the training time. In PyCaret, this can be achieved using feature_selection parameter)

###### remove_multicollinearity=True (Multicollinearity (also called collinearity) is a phenomenon in which one feature variable in the dataset is highly linearly correlated with another feature variable in the same dataset. Multicollinearity increases the variance of the coefficients, thus making them unstable and noisy for linear models. One such way to deal with Multicollinearity is to drop one of the two features that are highly correlated with each other. This can be achieved in PyCaret using remove_multicollinearity parameter within setup)

###### multicollinearity_threshold (Threshold used for dropping the correlated features. Only comes into effect when remove_multicollinearity is set to True)

###### ignore_low_variance= True (Sometimes a dataset may have a categorical feature with multiple levels, where distribution of such levels are skewed and one level may dominate over other levels. This means there is not much variation in the information provided by such feature. Such features are eliminated when this is set as True)



Step 3: The final submission file (with Accuracy value of 88%) that is submitted to the Hackathon is named under this directory "loan_approval_pycaret.csv"

Step 4: The saved model is loaded in the form of .pkl file which can be used for deployment. .pkl file is large to upload. It was compressed and stored with in repository as "Final CatBoost Classifier Model 28Jul2020.rar"

A PKL file is a file created by pickle, a Python module that enabless objects to be serialized to files on disk and deserialized back into the program at runtime. It contains a byte stream that represents the objects.

The process of serialization is called "pickling," and deserialization is called "unpickling." A PKL file is pickled to save space when being stored or transferred over a network then is unpickled and loaded back into program memory during runtime


![loan](https://user-images.githubusercontent.com/65406908/88794372-65094180-d16c-11ea-8df7-4a8614ed2b65.jpg)



Predict Loan Eligibility for Dream Housing Finance company
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 



![d1](https://user-images.githubusercontent.com/65406908/88794251-2e332b80-d16c-11ea-954d-fc36b81770ee.PNG)


![d2](https://user-images.githubusercontent.com/65406908/88794283-38edc080-d16c-11ea-8a3c-1cc20fca28ed.PNG)


![d3](https://user-images.githubusercontent.com/65406908/88794308-42772880-d16c-11ea-8afa-b3c286b9cf04.PNG)


