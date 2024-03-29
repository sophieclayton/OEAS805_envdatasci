# OEAS895: Advanced Data Science Techniques in Ocean, Earth and Environmental Sciences

3 credits, Spring 2023   
Dr Sophie Clayton, [sclayton@odu.edu](mailto:sclayton@odu.edu)   
Office hours:  13:00 - 15:00 M, OCNPS 423  
Class times: 9:30 - 10:45 T/Th, OCNPS 403  
[Link to syllabus](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/OEAS895_AdvData_syllabus_Sp23.pdf)  
Students will require a laptop, all computational tools used in the course are available for free.

## Course description
The Ocean, Earth and Environmental Sciences are quickly moving from being a data-poor to  data-rich disciplines, with many scientific and industry-related applications enabled by the analysis, synthesis and statistical modeling of large and diverse environmental data sets. 

This is an advanced computational analysis course designed to introduce students to data management and analysis methods commonly used in data science applications. The data analysis portion of the course will be primarily based on machine learning methods. The course will also give an overview of a selection of scientific databases which host freely available oceanographic data and output from numerical model simulations. This course is not discipline specific and will be useful for any students who want to work with data efficiently and gain experience in data management, proper techniques in developing analytical pipelines and applying machine learning to their research.

The class will meet two days a week, Tuesday and Thursday. Classes will consist of a combination of lectures, discussions and practical coding exercises where collaboration and teamwork will be encouraged. The outcome of the course will be an individual capstone project where each student applies the techniques learned during the course to undertake a data analysis project based on their own research interests using at least 2 different data sources from open scientific databases, and may include data that they have generated themselves. Students will be expected to publish the code developed and results of their project in a public GitHub repository. 

## Course schedule with links to notes
A pdf of the schedule can be found [here](https://github.com/sophieclayton/OEAS805_data_science/blob/master/OEAS895_AdvData_schedule.pdf) 

| Week | Topic | Notes and code| Homework |  
|------|-------| ----------| --- |
| 1 (1/10)| Open Science and FAIR data | [Lecture slides](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/slides/OEAS895_intro_fairdata.pdf) |  | |
| 1 (1/12)| Version control, git, GitHub | [Version control overview](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notes/version_control.md), [Intro to git](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notes/git_exercise.md) | [HW1](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/homework/HW1_git_github.md) (due January 25<sup>th</sup> 5pm) |
| 2 (1/17)| Data science workflow and project organization | [Data science workflow overview](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notes/data_project_setup.md), [Project organization](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notes/project_organization.md) | |
| 2 (1/19)| Intro to environments, Exploratory Data Analysis | [conda notes](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notes/conda_package_manager_overview.md), [conda cheatsheet](https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf), [EDA with pandas jupyter notebook](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/EDA_example.ipynb) | |
| 3 (1/24)| Plotting with seaborn, more pandas EDA |  | [HW2](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/homework/HW2_EDA_envs.md) (due February 3<sup>rd</sup> 5pm) |
| 3 (1/26)| Environmental databases and toolboxes, mapping with cartopy|  [List of databases](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notes/data_resources.md), [making a map with cartopy](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/cartopy_map_example.ipynb), [plotting data on a map](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/cartopy_example2.ipynb)  |  |
| 4 | NO CLASSES | -- | -- |
| 5 (2/7)| Machine learning overview | Notes TBA | |
| 5 (2/9)| Intro to [scikit-learn](https://scikit-learn.org/stable/) and Supervised Regression | [Nitrate linear regression example](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/nitrate_linear_regress_example.ipynb) | [HW3](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/homework/HW3_regression.md) (due February 22<sup>nd</sup> 5pm) |
| 6 (2/14)| Scaling, Neural Network Regressors, Nearest Neighbor Regressors, in class practice| [Examples of different regression estimators](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/regression_examples.ipynb)|  |
| 6 (2/16)| Supervised learning - classification, evaluation and error metrics | Notes TBA |  |
| 7 (2/21)| In class practice | | [HW4](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/homework/HW4_classification.md) (due March 8<sup>th</sup> 5pm) |
| 7 (2/23)| Supervised learning - KNN and MLPClassifier | iris dataset examples: [KNN classifier](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/iris_KNN_example.ipynb), [MLPClassifier and feature scaling](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/iris_neuralnet_example.ipynb) | |
| 8 (2/28)| Unsupervised learning - KMeans | [KMeans example](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/KMeans_unsupervised_example.ipynb) using the seeds dataset| |
| 8 (3/2)| Unsupervised learning and Capstone Project Development | | [HW5 Capstone Proposal](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/homework/HW5_capstone_proposal.md) (due March 17<sup>th</sup> 5pm) |
| 9 | NO CLASSES | SPRING BREAK | -- |
| 10 (3/14)| Dimensionality Reduction, Feature Extraction with PCA | [PCA feature extraction example](https://github.com/sophieclayton/OEAS805_envdatasci/blob/master/notebooks/wine_PCA_example.ipynb) using the wine dataset| |
| 11 (3/21)| Feature Selection methods | |  |
| 11 (3/23)| Thursday: Project work | | |
| 12 (3/28)| Cross-validation for training models on small datasets| |  |
| 12 (3/30)| Thursday: Project work | | |
| 13 (4/4)| Paper discussion | |  |
| 13 (4/6)| Thursday: Project work | | |
| 14 (4/11)| TBD | |  |
| 14 (4/13)| Thursday: Project work | | |
| 15 (4/18)| Project Presentations | | Capstone Presentation Instructions|
| 15 (4/20)| Project Presentations | | |
<!---
--->

## Learning objectives
1. Understand FAIR data principles and how to apply them when generating, sharing and accessing data.
2. Develop a working knowledge of existing ocean and earth science databases and how to efficiently access data from them, including via APIs.
3. Students will develop their own data analysis toolbox using, but not limited to, Python and shell scripts.  
4. Understand and use version control (e.g. git), environments (e.g. conda) and code repositories (e.g. GitHub) to manage and share code.
5. Understand the underlying principles of machine learning techniques for regression and classification, including supervised and unsupervised learning and apply them to a targeted research question.
6. Understand the process of model evaluation and optimization and commonly used metrics for reporting model performance. 

## Capstone Project
The goal of the final capstone project is to assess students ability to combine and apply the skills learned in class in the context of a real-world research problem. The class will mostly focus on tools for data analysis, visualization and developing and evaluating machine learning models, so this will be the focus of the capstone project. Students must have the dataset(s) and general scope of their capstone project approved by the instructor the week after spring break. 

Detailed information on the capstone project is posted [here](/homework/capstone_instructions.md).

