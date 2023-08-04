# University Admission Predictor


## Objective  
Given certain class 12 student, our task is to predict the probability of the student getting seleceted into graduate programs. We will use a random forest to complete this task.

## Dataset
The dataset contains 500 observations with the following variables:  
**GRE Score** - Out of 340  
**TOEFL Score** - Out of 120  
**University Rating** - Between 1 to 5 (5 being the best)  
**SOP** - Between 1 to 5 (5 being the best)  
**LOR** - Between 1 to 5 (5 being the best)  
**CGPA** - Out of 10  
**Research** - 1 if student has research experience, else 0  
**Chance of Admit** - Probability of getting accepted into graduate program

Take 80% of the data for training, the other 20% will serve as a validation set.

## Outline  
The following procedures are carried out in the notebook:
### Analyzing the Attributes  
Determine what predictor variables are useful for the task at hand. Apply appropriate transformations if needed.
### Model Fitting
In this case, use a Random Forest to make predictions. Find optimum parameters and record metrics.
### Evalutaion Metrics
Evaluation Metrics for this project are Mean Squared Error **(MSE)** and coefficient of determination **R^<sup>2</sup>**. Apart from evaluation metrics, we also analyze feature importance. 
### Predicting on a Custom Example
Provide a test case and look at the prediction.

## Conclusion
The final model explained about **78.9%** of the variability in **Chance of Admit**.  




