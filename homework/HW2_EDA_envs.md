# OEAS895 Homework 2: EDA and environments - due 5pm February 3<sup>rd</sup>

Create a new folder in your OEAS895 repository called `HW2` where you will save the code and files you create for this homework assignment. You will also create a new conda environment called `hw2_env` including all of the packages you need to complete your assignment.

You will be working with the `International_Coastal_Cleanup.csv` dataset shared in the `data` folder. This dataset is open data provided through the [Norfolk OpenData Portal](https://data.norfolk.gov/). Detailed information on the International Coastal Cleanup dataset is provided [here](https://data.norfolk.gov/Environment/International-Coastal-Cleanup/frs3-vh3y).

## Part 1 (45 points): Exploratory Data Analysis
For this part of the homework, you will create a Jupyter notebook to explore the International Coastal Cleanup data. You should use the tools in the `pandas` `seaborn` and `cartopy` packages for your analyses, in addition to any other relevant or useful packages you wish to use.

Remember that EDA is a fundamental step in data analysis, and the goal of EDA is to investigate and understand the structure and content of your dataset, to generate some understanding of your data through the use of descriptive statistics and to summarize key insights. 

As a guide, the following elements and analyses should be included in your EDA:  

*  Size of your data set. How many variables does it contain? How many samples/data points (e.g. rows of data)?  
*  Data types in your data set. Are all of the variables the same type? Do you have a combination of types?  
*  Do your data columns contain missing data? Do all variables have the same number of missing data points?  
*  Descriptive statistics for your variables of (mean, stdev, median, etc...). Boxplots, bar charts and histograms are great for visualizing the distribution of your data.  
*  Does your data contain outliers? 
*  How do your variables relate to each other? You might look at correlations, scatter plots and/or correlation matrices.
*  What initial conclusions can you draw from your exploration of the data?

**NOTE:** I do not expect you to use any data other than what is included in the file provided. You are likely to think of questions that require additonal data sources, but that is not expected for this assignment.

In addition to executing commands to address the questions above, you should include text within your jupyter notebook to give background information on the dataset, to explain what you find at each step and give your thoughts on it. This should be included as cells containing text formated with [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) (as I have done in the `EDA_example.ipynb` notebook).

Once you are happy with your EDA jupyter notebook, commit it locally using git and push your work to your GitHub repository.

## Part 2 (5 points): Sharing your environment
You also want to share your `hw2_env` environment so that someone else might download and run your EDA jupyter notebook without dealing with version conflicts. Following the steps in the conda notes and cheatsheet, save your `hw2_env` environment information to a `.yml` file called `hw2_env.yml`. Commit this file locally using git and push it to your GitHub repository.


## Homework submission:
To submit your homework, send me a direct message via Slack with the link to your github repository containing your HW2 folder which should have your EDA juputer notebook and `hw2_env.yml` files saved in it. 

Your homework is due by **5pm on February 3<sup>rd</sup>** and will incur a 10% per day late penalty if submitted after the deadline. I will not accept any work submitted after midnight on February 5<sup>th</sup>.
