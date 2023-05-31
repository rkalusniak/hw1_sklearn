# hw1_sklearn



Documentation
==================

This project uses logistic regression models to examine the housing data and create various models. Some of the topics include:
* Pipelines	
* Normalization
* Cross-Validation
* GridSearchCV
* Decision Trees
* Error Testing



Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── hw1_sklearn	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   hw1)sklearn_output.ipynb	<- A Jupyter notebook to  complete the tasks for this asskignment
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder





Development workflows
=======================
This project uses a cookiecutter described below. Below are the project steps provided by the cookiecutter.

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter https://github.com/misken/cookiecutter-datascience-aap
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named hw1_sklearn, then do;

```bash
git remote add origin git@github.com:rkalusniak/hw1_sklearn.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.
