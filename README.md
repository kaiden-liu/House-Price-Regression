# House-Price-Regression : Project Overview 
* EDA on the topic house price and determine variables(Overall Quality and Above Ground Living Area) that influence Sale Price of houses the most
*Tried Lasso and Linear Regression for this dataset to find a better model
* Features engineering with the data set:
  *  Dealing with missing values
  *  Log transformation: some highly skewed variables
  *  Dummy Variables: Many categorical variables

# Code and Resources Used:
**Jupyter Notebook Version:** 5.7.4  
**Python Version:** 3.7.1  
**Packages:** Pandas, Mathplotlib, Numpy, Seaborn, SciKit-learn, SciPy  
**Data Source:** https://www.kaggle.com/c/house-prices-advanced-regression-techniques  
**Tutorials:**
  * https://www.kaggle.com/serigne/stacked-regressions-top-4-on-leaderboard#Stacked-Regressions-to-predict-House-Prices
  * https://www.kaggle.com/dejavu23/house-prices-eda-to-ml-beginner#Part-0-:-Imports,-Settings,-Functions
  * https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python
  * https://markdown-guide.readthedocs.io/en/latest/basics.html#headers
# Data fields
Here's a brief version of what you'll find in the data description file.   
The full list can be found in the file **data_description.txt**

* SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.
* MSSubClass: The building class
* MSZoning: The general zoning classification

# Data Cleaning
The data set consists of some outliers as well as null values:  
* Removed columns that consisted too many null values if the result improves the model  
* Removed one data point with null value recorded in the column "Electrical"  
* Removed variables that showed strong correlations with other variables and have low correlation with the target variable  

# Data Visualization
Below are some highlights of grpahs that I found interesting
![alt text](https://github.com/kaidenliu0806/House-Price-Regression/blob/master/images/boxplot.png "Boxplot for Overall Quality")
![alt text](https://github.com/kaidenliu0806/House-Price-Regression/blob/master/images/heatmap.png "Heatmap for Correlation")

# Result:
I tried Linear Regression and Lasso for predictions of the test set. The results were not too successful as the prediction of Sale Prices are very low (eg: 900). My guess for the inaccuracy of the prediction is due to the order of my codes. There might be some order problems that I made that interfered with the data set slightly.     
  
This is my first project and my original plan is to translate my statistical knowledge and data skills from R to Python, to prepare me to work on an end to end project. Overall, it is a great success for me.

**Thank you for being interested in my project and definitely let me know for any improvements**

