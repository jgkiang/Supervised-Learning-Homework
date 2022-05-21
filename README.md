# Supervised Machine Learning Homework - Predicting Credit Risk

In this assignment, you will be building a machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not. 

<b>**PLEASE SEE MY HOMEWORK ANSWERS BELOW IN BOLD</b>

## Consider the models

You will be creating and comparing two models on this data: a logistic regression, and a random forests classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook or in a separate document) your prediction, and provide justification for your educated guess.

<b>I am picking random forest because in general cases, they have better average accuracy.</b>

## Fit a LogisticRegression model and RandomForestClassifier model

Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. You may choose any starting hyperparameters you like. Which model performed better? How does that compare to your prediction? Write down your results and thoughts.
<br><br><b>Without scaling the data, my prediction -- random forest -- was correct.</b>

## Revisit the Preprocessing: Scale the data

The data going into these models was never scaled, an important step in preprocessing. Use `StandardScaler` to scale the training and testing sets. Before re-fitting the LogisticRegression and RandomForestClassifier models on the scaled data, make another prediction about how you think scaling will affect the accuracy of the models. Write your predictions down and provide justification.

Fit and score the LogisticRegression and RandomForestClassifier models on the scaled data. How do the model scores compare to each other, and to the previous results on unscaled data? How does this compare to your prediction? Write down your results and thoughts.

<b>My prediction after scaling, is that logistic regression will be more accurate.  I was correct in my prediction on the test score because logistic regression relies on scaled data, while random forest does not. Now the training score for random forest in the unscaled was already perfect and that did not change when using scaled data. I am unsure as to why the unscaled random forest score was perfect and I believe that warrants further examination.</b>


