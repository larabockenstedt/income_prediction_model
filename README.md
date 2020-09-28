# income_prediction_model
In this project for OpenClassrooms, a bank is looking to target new potential customers who are more likely to have higher incomes later in life. The goal of the project is to create a model to predict a person's future income.

## About the Project
The first notebook — task one — of the project includes the code for cleaning the necessary datasets from the world income distribution. They include: 
* Income, in percentiles, for each country
* The Gini Index for each country
* The population of each country
After, in the same notebook, is a short preliminary analysis that looks at the:
* Year(s) of data
* Number of countries involved
* Population covered by the dataset (percentage of world population)
* The dollar PPP unit and an explanation of why (not why not) it's a good method to compare countries 
* A graph showing how diverse countries are in terms of income distribution. This graph must represent the income (y-axis, on a log scale) as a function of income class (x-axis) for 5 to 10 countries. Please ensure you represent a diversity of cases. Among the countries that must be present : your own country, and the two countries that have the greatest and lowest Gini index.
* The Lorenz curve for these countries

The second notebook — titled Task 2 — centers of generating the dataset needed to make the income prediction models. Using the research papers as a guide, the parent's income class is generated as well. At the end of the notebook, the datasets columns included:

* The country's name (countryname)
* The child's income class (c_i_child)
* The child's income (y_child)
* The elasticity coefficient (base_case)
* The Gini Index (gj)
* The mean income by country (mj)
* The parent's income class (c_i_parent)

The third notebook — Task 3 — income involves comparing several linear regression models, using an ANOVA, and using logged versions of the same models to find the best model for making an income prediction. At the end of the notebook, the chosen model is compared with the researcher's findings, and is used to make an income prediction. 

The new_functions.py file was used to help with the kmeans clustering, and was created by OpenClassrooms for a course.

## Built With
This project was built using Jupyter Notebook.

# Getting Started
I recommend clicking the green “clone or download” button and then downloading the ZIP file. Another option is to fork the repo and clone it locally. The process to do so is explained here: https://help.github.com/en/github/getting-started-with-github/fork-a-repo

To install Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html
To install Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html

## Requirements
Python >= 3.7.4

## Tests
Tested on macOS 10.14.6 with Jupyter Notebook, using Python 3.7.4

# Contributing
Contributions are greatly appreciated. Start with forking the project. Then: 
1. Create a Feature Branch (git checkout -b feature/feature)
2. Commit Changes (git commit -m 'Add some feature')
3. Push to the Branch (git push origin feature/feature)
4. Open a Pull Request

# License
MIT license

# Contact
Lara Bockentedt - @larabockenstedt - larabockenstedt@outlook.com
