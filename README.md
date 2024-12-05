# Machine-Learning-for-User-Classification-Project
## Using Machine Learning to Classify Students and Predict Student Purchases

## Case Description

### Background:
In a machine learning classification problem, the algorithm assigns labels to instances based on their features. This Marchine Learning for User Classification project will allow you to apply this technique by utilizing an excerpert of our own data stripped of personally identifiable information. I will examine student engagement metrics, such as the number of days sutdents have spent on the platform, the minutes of watched content, and the number of courses they´ve started. You´ll then use this data to train several machine learning models, inlcuding logistic regression, k-nearest neighbors, support vector machines, dcision trees, and random forests. The aim is to predict wether students would upgrade their free plan to a paid one.

### Business Objetive:
Such an analysis is of utmost importance for any online company. Predicting potencial customers can be used for advertisement targeting or reaching out with exclusive offers. This helps allocate a budget for users likely to benefit from the product, aiming to increase the company´s revenue.

### Note:
This classification problem deals with a heavily imbalance dataset, the number of students likely to keep their free plan exceeds the number predicted to purchase.

## Project requirements
I worked with Python for this Marchine Learning for User Classification project, wher you´ll need to prepare the following libraries:
 •	Pandas
 •	matplotlib
 •	statsmodels
 •	scikit-learn
 •	numpy
 •	seaborn

 ## Project files
 •	ml_datasource.csv - the file contains the database for the project.
 •	Machine Learning Project.ipynb - the notebook contains a skeleton of the project for each task.


 ## Project content
 •	2 Project files
 •	Part 1: Data Preprocessing
 •	Part 2: Creating a Logistic Regression Model
 •	Part 3: Creating a K-Nearest Neighbors Model
 •	Part 4: Creating a Support Vector Machines Model
 •	Part 5: Creating a Decision Trees Model
 •	Part 6: Creating a Random Forests Model
 •	Part 7: Results Interpretation
 
 ## Results Interpretation

 I asked the following questions, for the interpretation task:
   1. What is the LLR (Log Likehood Ratio) p-value in the summary of the logistic regression model, and what does it tell us?
      The LLR p-value is a statistic used to test if a logistic regression model iis "useless", i.e., statistically different from a model with no predictors. The p-value we obtained for the model is 0.000, samller than 0.050, which indicates that our model is     
      statistically significant. 
   2. What is the equation of the logit model, considering only statistically significant variables?
      Statistically insignificant variables are those with a p-value equal to or larger than 0.05. The only such variable is x4, corresponding to practice_exams_passed, with a p-value of 0.270.
   3. Which are the features that influence the decision in the decision tree model?
      The decision tree shows that the only features influencing the decision are days_on_platform and minutes_watched. The boxes where these features appear are highlighted in the figure below.
   4. What observations and conclusions can you make on the confusion matrices? Does the accuracy of the model determine its predictive power?
      
   5. How can we use the results from the models?
   6. What actions can w undertake to improve the models?
 
