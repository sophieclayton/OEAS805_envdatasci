# Structuring a data science project
By spending a little time up front to set up a structure for the data, code, figures and documentation that will constitute your project, you will save yourself time, make it more likely that your project is reproducible and easier to share with others.

### Project components
* DATA
	* **Raw data**, the original data. These files should **never** be modified. Treat these files as read only to preserve their provenance. You might even opt to make this folder read-only to ensure that the original data are not modified.
	* **Clean data**, this is where you will save data that has been cleaned and is ready for analysis and model development.
	* **Results/Output**, you might 
* CODE
	* **Exploratory Data Analysis**, often in the form of Jupyter notebooks
	* **Model development**, may be a combination of Jupyter notebooks and scripts, but if you plan to deploy the model on a large(r) scale, you'll move to scripts
* VISUALIZATIONS
	*  **Figures** should have their own folder
* DOCUMENTATION
* REQUIREMENTS
	* A `README.md` file that gives a brief but detailed overview of your project.
	* 	Projects often include a `requirements.txt` or `environment.yml`file that lists the code packages and versions used.   
* REPORTS/MANUSCRIPT

## Resources
* [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/#cookiecutter-data-science): provides a standardised, customisable template for data science projects. The documentations does a great job of explaining why this is a good idea.
* [How to write a good README file](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/): this is a good general write up of what you should include in your README