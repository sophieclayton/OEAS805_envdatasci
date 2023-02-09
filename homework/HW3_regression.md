# OEAS895 Homework 3: Building and applying a regression model - due 5pm February 17<sup>th</sup>

Estimating nitrate concentrations from BGC Argo float data using a model based on the JMA repeat hydrography data.

This assignment builds on the in-class work we did this week building a model to predict nitrate concentrations in the North West Pacific from the Japan Meteorological Association repeat hydrography data (‘JMA_nitrate.csv’). 

In groups, you built a model using either Lasso or ElasticNet, and have done a sensitivity assessment to find the best set of model parameters to predict your test data.

Continue to work on this project in your groups, and upload one jupyter notebook for each group’s results.

For this assignment, use your model to estimate nitrate from the BGC Argo profiles found in the ‘/data/kuro_BGCArgo_noNO3.csv’ file. I have also provided you with the full BGC Argo dataset in ‘/data/kuro_BGCArgo_NO3.csv’ so that you can assess your model performance

## Part 1 (20 points): EDA
Before you apply your model, assess the level of overlap between the range of environmental conditions represented in the JMA and BGC Argo data sets. 
* Compare the geographical extent, depth range, water masses, seasonal coverage and any other factors that you think could be pertinent between the two data sets.
* Describe similarities and highlight differences.

## Part 2 (40 points): Model application and evaluation
Apply your trained model to the BGC Argo data to estimate nitrate concentrations based on your input variables (e.g. temperature, salinity, etc…).

Compare the observed BGC Argo nitrate to the values predicted by your model. 
* Report the r2 score and RMSE (root mean squared error). 
* Does your model perform consistently well, or are there any noticeable outliers? If there are, identify those data points and suggest reasons why you think that your model performs less well for those points.

## Homework submission:
To submit your homework, send me a direct message via Slack with the link to your github repository containing your HW3 folder, which should have your jupyter notebook saved in it. You may submit one notebook for each group. Ensure that the name of each of the group members is included in the notes in your notebook.

Where I ask for written analysis of your results, write it up in a markdown cell in your jupyter notebook.
For more information on markdown formatting:   
[https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)  
[https://www.markdowntutorial.com/](https://www.markdowntutorial.com/)

Your homework is due by **5pm on February 17<sup>th</sup>** and will incur a 10% per day late penalty if submitted after the deadline. I will not accept any work submitted after midnight on February 19<sup>th</sup>.
