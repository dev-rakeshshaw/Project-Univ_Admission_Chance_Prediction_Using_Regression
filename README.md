# Project-Univ_Admission_Chance_Prediction_Using_Regression
 
Brief introduction Goals In this project, we will be using the Admission_predict dataset in csv format to predict the chances of students getting admission by a university based on several academic performance measurement. To yield the most accurate result, we will be going through several steps such as Standard Scaling,feature selection, cross validation, Distribution Cheking,Outlier Checking, etc. to train a linear regression model, make prediction and measure its performance.

Dataset information:

The data contains 500 rows and 9 columns :

Serial No. : ID of the data

GRE Score : GRE score (dbl, 0 - 350)

TOELF Score : TOEFL score (dbl, 0 - 120)

University Rating : Rating of the university, (integer, 1 - 5)

SOP : Strength of the Statement of Purpose (integer, 1- 5)

LOR : Strength of the letter of recommendation (integer, 1 - 5)

CGPA : Undergraduate GPA (dbl, out of 10)

Research : Research experience (integer,0 : none, 1 : yes)

Chance of Admit : Admission (dbl, 0 - 1) It is the response variable, which is a continuous value between 0 and 1, indicating the chances of getting admission
