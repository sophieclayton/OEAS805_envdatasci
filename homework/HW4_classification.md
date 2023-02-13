# OEAS895 Homework 4: Building and applying a classification model - due 5pm March 8<sup>th</sup>

Use error metrics to explore the parameter space of your neural network classifier.

For this exercise you will use the ‘wine’ dataset available as a sci-kit learn dataset, and the multi-layer perceptron classifier (MLPClassifier). 

## Part 1 (10 points): Model construction
Following the method that we have discussed in class, build an MLPClassifier model to predict the target variable from the feature data. 

## Part 2 (30 points): Explore hyperparameter space
You will explore the parameter space of the MLPClassifier model and determine the combination(s) of number of layers and number of neurons that yield the best model accuracy score. 

* Produce a figure that illustrates the results of your analysis. Write a short paragraph explaining your results. If more than one combination of layers/neurons results in a high accuracy score (>0.9), discuss which combination of layers/neurons you would use and why.

* For each combination of layers/neurons that yields an accuracy score > 0.9, calculate the confusion matrix, precision, recall and f1-score for each target class. Describe the implications of your results for model performance for each target class and choose which layers/neurons you will use in the final version of your model.

## Part 3 (20 points): Apply your tuned model
Use the final version of your model, developed using the steps above, to predict the class for the ‘unknown’ samples found in the `unknown_wine.csv` file. 

Find a scikit-learn function that will give the probability that each unknown wine fits into each of one of the three target classes. List the probabilities for each unknown sample for each target class and comment on your results.


## Homework submission:
To submit your homework, send me a direct message via Slack with the link to your github repository containing your HW4 folder, which should have your jupyter notebook saved in it. 

Where I ask for written analysis of your results, write it up in a markdown cell in your jupyter notebook.
For more information on markdown formatting:   
[https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)  
[https://www.markdowntutorial.com/](https://www.markdowntutorial.com/)

Your homework is due by **5pm on March 8<sup>th</sup>** and will incur a 10% per day late penalty if submitted after the deadline. I will not accept any work submitted after midnight on March 10<sup>th</sup>.
