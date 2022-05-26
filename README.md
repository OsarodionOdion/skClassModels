# classification_models_sklearn

**Building Classifier Models to Predict House Prices in King County, USA**

**Goal:** The objective of this project is to build classifier models to predict a binary variable (price_gt_1M) that determines if the value of a house is greater than/equal to 1 million or less than 1 million. A requirement for this project is the use of sklearn pipelines that contain the preprocessing steps and the model estimation step

Files
------

All completed work for this project is contained in the `skclass_model_hs.ipynb` file. The `hw1_sklearn_dataprep.ipynb` contains all data preparation by Prof. Mark Isken, School of Business, Oakland University. Automated EDA reports are available in the output folder

Contents of the skclass_model_hs.ipynb file
---------------------------------------------

The EDA section covers analysis of the data sets used in this project. The section on logistic regression covers various logistic regression models used to predict the target variables.

Cookie cutter used in placing project under version control was created by Prof. Mark Isken.



Information on using this cookiecutter

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:osarodion/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named classification_models_sklearn, then do;

```bash
git remote add origin git@github.com:osarodion/classification_models_sklearn.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── classification_models_sklearn	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder


Documentation
--------------

In this very simple project structure template, we've just included a markdown file with some typical
section headings to use for project notes. Expand as desired. Later in the semester we will learn how to
use Sphinx with restructuredText to write and generate documentation.



