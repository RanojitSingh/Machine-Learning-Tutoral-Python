In this module we will learn how to deploy or use a exixting model. Meaning we have created a model
and now we want to use it for prediction. We cannot use the python file every time for prediction because
the python file is created to build and train the model. In real world once we create the model we will deploy 
in production and we do not train the model everytime we feed data into it, instead we will use the model and 
supply data so that it will pridict.

For creating a model file we need to export the file into pickle/joblib file then we need to use the pickle/joblib file in production
--Pickle is a seperate module
--joblib found in sklearn module

which module is best- If many numpy array has been used in the model it is suggested to use joblib file

We are using old machine learning model for getting the knowledge, how we can use the model file. 

Existing model file name is - 1.Machine Learning Tutorial Python _ 2 Linear Regression Single Variable.ipynb

How to export the model to pickle/joblib file is written in 1.Machine Learning Tutorial Python _ 2 Linear Regression Single Variable.ipynb
How to use pickle/joblib file is written in Save Model Using Joblib And Pickle.ipynb