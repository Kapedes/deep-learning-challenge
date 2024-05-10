# deep-learning-challenge

Overview of the analysis: 

Purpose of this analysis:
The purpose of this analysis is to develop a deep learning model to predict whether applicants to Alphabet Soup will be successful if funded based on various features provided in the dataset. By accurately predicting success, Alphabet Soup can optimise its funding allocation process and increase the impact of its contributions. A desired result of 75% is being anticipated to be achieved. 

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

1. The variable that was the target for the model was "IS_SUCCESSFUL" with (1) standing for yes and (0) as standing for no. 

2. The variables that are features for the model were:
"APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "INCOME_AMT," "SPECIAL_CONSIDERATIONS," and "ASK_AMT."

3. The variables removed from the dataset were:
"EIN" and "NAME" columns are identification columns were removed from the dataset. The reason for this is that they are neither Features or Targets.

Compiling, Training, and Evaluating the Model

4. I varied the number of neurons Base case (ie 80, 30, 32) ReLU activation functions were chosen for the hidden layers to introduce non-linearity and enhance the model's capacity to learn complex patterns in the data.

5.  The target model performance of 75% was not achieved. 

6.  I adjusted both the number of epochs and the neurons to increase model performance. However further iterances are required to achieve the 75% threshold.

In summary, the deep learning model did not achieve the 75% target threshold. Further optimising is necessary to enhance the model's accuracy and reliability. A random forest is another model than can be used to yield a better result as it offers enhanced interpretability and handles non-linear relationships well, and can handle large datasets efficiently. 
