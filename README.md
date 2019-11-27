# Fundamentals-of-Data-Analysis-Project-2019

This repository contains my project 2019 for the module Fundamentals of Data Analysis at GMIT. See here for the instructions: https://github.com/ianmcloughlin/project-2019-fundda/raw/master/project.pdf. References and resources I used in compiling this project are listed in the references section at the foot of this Readme file and also throughout my jupyter notebook.

## Author
John Dunne

## About this Project
This project concerns the well known tips dataset and the Python packages Seaborn and jupyter. In completing this project I will download the tips dataset and use the Python packages Seaborn and jupyter to perform some analysis on the dataset in order to explain the dataset in detail. I will also endeavour to analyse whether there is a relationship between the total bill and tip amount.  

## How to download this repository
1. Go to GitHub.
2. Go to my repository: https://github.com/johndunne2019/Fundamentals-of-Data-Analysis-Project-2019
3. Click the clone/download button.
4. Save the repository to a local folder location on your machine.
5. You will need to navigate to this folder location on the command line in order to run the program.
6. Details on how to view my jupyter notebook are described in the next section below.

## How to run the jupyter notebook
1. On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd change directory command.
2. Type jupyter notebook on the command line and press enter
3. After a short wait jupyter notebook will open in your web browser. 
4. Open the Tips-Dataset.ipynb notebook in the browser and the notebook containing the code and comments that I wrote for this assignment will be displayed.
5. if you want to run the code in any cell hold down the shift key and press enter and the command will run and the output wil be displayed in the next cell. 
6. To change between edit and read mode at any time press the ESC key.
7. When you have finished viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to kill the program.

# Plan for completing this assessment
**I will break the assessment into 3 sections of work containing subsections:**

**1. Description:**
* Create a git repository and make it available online.
* Within the git repository create a jupyter notebook.
* Download the Tips Data set and within the jupyter notebook use some descriptive analysis on the data set. 
* Try to use the Seaborn and pandas packages to describe the data set. 

**2. Regression:**
* Add a section to the jupyter notebook that discusses and analyses whether there is a relationship between total bill and tip amount. 

**3. Analyse:**
* Analyse the relationship between the variables in the Tips data set. 

**In addition to the above I will:**
* Keep a detailed list of all references and reading I complete and make these available.
* Provide details in this Readme file on the packages I have used to analyse the Tips data set. 
* Provide an overview of the Tips data set and the analysis I have conducted within this Readme file.

# Python packages I used in my analysis of the Tips dataset

## Jupyter lab
In completing this project I have set up this repository and created a jupyter lab notebook in which I will write some code to analyse the tips dataset. I viewed the lecture videos on jupyter notebooks and also completed additional reading in order to familiarise myself with jupyter. Both jupyter notebook and jupyter lab were discussed in lecture videos and I also did some additional reading about the differences between both https://ipython-books.github.io/36-introducing-jupyterlab/ and https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906. Following this research I decided to use jupyter lab for my project. 
The jupyter lab tutorial is here: https://jupyterlab.readthedocs.io/en/stable/

**Some interesting facts I learnt about jupyter lab**

* jupyter notebooks contain cells and the user can enter as many arguments as they like in each cell however jupyter will only return the result of the last entered argument in the cell by default. In order to have the results of all arguments in a cell returned the user must wrap each argument in a print statement.
* jupyter acts like ipython with the key difference that the user interacts with the jupyter browser which offers an extra layer of functionality including the user can use the mouse to move around and select different areas of the notebook. 
* There are 2 different modes when viewing a cell in jupyter, edit mode which appears in green on the left side of the cell and read mode which appears in blue on the left side of the cell.
* There are 2 different modes that can be used when writing in a jupyter notebook - markdown and code. To move between the 2 modes when writing in a notebook the user can hit the ESC key and then M to move to markdown mode and Y to move to code mode. 
* When a user wants to execute an argument they should hold down the shift key and press enter and the output will be displayed in the notebook. 
* There are keyboard shortcuts that can be used, one example is a which adds "a" new cells above the cell the cursor is currently located in and "b" which adds a new cell below the cell the cursor is currently located in. A full list of keyboard shortcuts can be accessed in the help section of the jupyter browser. 
* The numbers that appears on the left side of the screen on the cells containing code indicate the order in which the commands were passed to the kernel. jupyter remembers the arguments that have been previously passed to the kernel. 
* The user can reset the kernel and clear output by going to the toolbar in the browser and selecting restart and clear output. When the user sends each argument to the kernel after this point they will see the numbers on the left hand side start again from 1. 

## Seaborn
Seaborn is a data visualization package within Python which is based on matplotlib. Seaborn can be used to make statistical graphics in Python. 

"Seaborn aims to make visualization a central part of exploring and understanding data. Its dataset-oriented plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots." 

Sourced from the official Seaborn documentation - https://seaborn.pydata.org/introduction.html

**Some useful links:**
* The official Seaborn tutorial: https://seaborn.pydata.org/tutorial.html
* Seaborn documentation: https://seaborn.pydata.org/index.html
* Youtube: https://www.youtube.com/watch?v=TLdXM0A7SR8

## pandas
Python Data Analysis Library is a Python package than can be used to analyse data sets such as the Tips data set. I used pandas to do some basic descriptive statistics on the Tips data set. pandas can deal with both strings and floating point numbers and so is a good package to use to analyse the Tips data set. 

**Some useful links:**
* pandas documentation: https://pandas.pydata.org/
* 10 minutes to pandas: https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html
* Wes McKinney - 10-minute tour of pandas - https://www.youtube.com/watch?v=_T8LGqJtuGc

## NumPy
NumPy is a Python package used for scientific computing and within NumPy there are many subpackages.The homepage is here: https://numpy.org/. I used NumPy in the regression section of my project to do some calculations around the best fit line including:

* numpy.mean: https://docs.scipy.org/doc/numpy/reference/generated/numpy.mean.html
* numpy.polyfit documentation: https://docs.scipy.org/doc/numpy/reference/generated/numpy.polyfit.html.
* numpy.corrcoef: https://docs.scipy.org/doc/numpy/reference/generated/numpy.corrcoef.html

## Scikit-learn
Scikit-learn is a machine learning library in Python built on top of NumPy, SciPy and matplotlib. Some of the uses of Scikit-learn include regression and Classification analysis. 

**Some useful links:**
* scikit-learn: https://scikit-learn.org/stable/
* Supervised learning: https://scikit-learn.org/stable/supervised_learning.html#supervised-learning
* Model selection and evaluation: https://scikit-learn.org/stable/model_selection.html#model-selection

Within the Scikitlearn library there is a Linear Regression model which is used to calculate linear regression using the Ordinary least squares (OLS) method. The documentation page is here: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression. I imported the model and calculated the slope, y intercept and R Squared values for the best fit line of total bill anf tip amounts. 

## matplotlib
matplotlib is a Python 2D plotting library and the homepage is here: https://matplotlib.org/. I used matplotlib.pyplot to plot the best fit regression line in section 2.3 of my jupyter notebook using the slope and y intercept values as calculated by NumPy.

# My jupyter lab notebook 

## Table of Contents
* Section 0: Introduction to the Tips data set
* Section 1: Descriptive Statistics and Plots to describe the Tips data set
    * Section 1.1: pandas to describe and analyse the Tips data set
    * Section 1.2: Seaborn to visualise the Tips data set
* Section 2: Regression
    * Section 2.1: Introduction to Regression
    * Section 2.2: Seaborn Linear Regression
    * Section 2.3: Simple linear regression - best fit line
    * Section 2.4: Scikit learn to analyse the linear relationship between total bill and tip amount
* Section 3: Relationship between the variables in the Tips data set
    * Section 3.1: Seaborn.pairplot
    * Section 2.2: Seaborn.catplot
    * Section 3.3: pandas and seaborn to analyse relationship between variables in the data set
* Section 4: Conclusion

## Section 0: Introduction to the Tips data set

The tips dataset can be viewed at this link: https://github.com/mwaskom/seaborn-data/blob/master/tips.csv which is saved in this repository: https://github.com/mwaskom/seaborn-data. The purpose of this repository is that the seaborn.load function when called downloads the csv tips data set from this location. This is convenient in that the user does not have to download the csv file to their own repository or machine in order to create analytics based on the data set. 
I have downloaded the Tips from this repository and saved it in my repository at this link: https://github.com/johndunne2019/Fundamentals-of-Data-Analysis-Project-2019/blob/master/Tips.csv. 

I found the below explanation on the background and contents of the Tips data set online: 

"In one restaurant, a food server recorded the following data on all customers they served during an interval of two and a half months in early 1990. The restaurant, located in a suburban shopping mall, was part of a national chain and served a varied menu. In observance of local law, the restaurant offered to seat in a non-smoking section to patrons who requested it. Each record includes a day and time, and taken together, they show the server’s work schedule."

Source: https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset

**What data is captured in the Tips dataset?**

The following is a breakdown of the data that is captured in the Tips dataset:

* There are 244 rows and 7 columns of data in the Tips data set. 
* The first column is called total_bill and this is the total amount of each bill in US dollars. 
* The second column is called tip and is the amount of the tip (gratuity) given by each party in US dollars.  
* The third column is the sex of the person paying for the bill. 
* The fourth column records if there was a smoker among the party ie- if the party sat in the smoking or non smoking section of the restaurant. 
* The fifth column of data shows the day of the week. 
* The sixth column of data shows the time of day- dinner or lunch. 
* The seventh and final column records the size of the party. 

## Section 1: Descriptive Statistics and Plots to describe the Tips data set

The Python packages I used in section 1 to perform some analysis on the data set were:

* **pandas**

I read in the data set with pandas and returned some descriptive statistics about the data set using some functions within the pandas library.

**Some of the functions within pandas that I used to analyse the dataset**
    * pandas.read_csv to read in the csv file to the pandas package. 
    * dataframe.head() to display the first 5 rows of the dataset. 
    * dataframe.tail() to display the last 5 rows of the dataset.
    * dataframe.describe() to return an overview of some basic statistics based on the dataset. 
    * dataframe.shape() to return the number of rows and columns in the dataset. 
    * dataframe.iloc to return a particular row of data from the dataset. 
    * dataframe.loc to return all rows of data in the dataset that have a certain condition such as all "male" and "smoker". 
    * dataframe.mean to return the mean of a row of data in the dataset.
    * dataframe.std to return the standard deviation of a row of data in the dataset.
    * dataframe.groupby to group the data set by variable.

* **Seaborn**

I used Seaborn to load in the data set and output some plots based on the data set and I explained how the different types of plots work and why they would be used in analysing a data set.

**Some of the functions within Seaborn that I used to analyse the dataset**
* Seaborn.relplot()
* Seaborn.distplot()
* Seaborn.countplot()

##  Section 2: Regression

**In this section I discussed and analysed whether there is a relationship between the total bill and tip amount.**

 In regression analysis their is a dependent variable and an independent variable: 

* Dependent variable - the variable you are trying to understand or predict
* Independent variable - the factors that have an affect on the dependent variable

In this case I want to analyse if there is a relationship between total bill and tip amount. So I could say:

* The dependent variable is - tip
* The independent variable is - total bill

**Section 2.2:**

First I used Seaborn to plot the regression line with the lmplot() and regplot() functions. The slope and intercept values are not returned using these functions but it gave me a good visual look at the regression line by calling these functions. I also had a look at the "hue", "markers" and "col" parameters with lmplot().

**Section 2.3:**

After viewing the lecture series of linear regression, I added a section to the jupyter notebook looking at simple linear regression and the best fit line. The slope and intercept of a best fit line can be calculated using numpy.polyfit or by using a calculation that I have explained in the notebook. After calculating the slope and intercept of the best fit line, I plotted the actual data points and the best fit line using matplotlib following the example we saw in lecture videos as a guide. I calculated the R Squared value of the best fitting line using numpy.corrcoef. The R Squared value is a measure of the strenght of the relationship between total bill and tip amount. 

**Section 2.4:**

I added another section looking at how Scikit learn can be used to calculate the slope, intercept and R Squared values of the best fit line. The linear regression model is imported from Scikit learn, x and y variables are passed in, and the the .fit command is called to fit the model to these variables. The following commands are then run:

* .intercept - returns the intercept of the best fit line.
* .coef - returns the slope of the best fit line.
* .score - returns the R Squared values of the best fit line.

**Regression - main findings:**
* The results of this regression analysis showed there is a relationship between total bill and tip amounts.
* From numpy.polyfit and Scikit learn linear regression model:
    * The slope of the best fit line was returned as: 0.10502452
    * The y intercept of the best fit line was returned as: 0.92026961
* From numpy.corrcoef and Scikit learn linear regression model the R-squared value was returned as: 0.45661658635167635 which I interpret to mean 45.6% of the data is accounted for by the regression model.
* This shows that their is a relationship between total bill and tip amount but that other factors may also play their part in determining tip amount etc.

## Section 3: Relationship between the variables in the Tips data set

In this section I analysed the relationship between some of the variables in the data set. I used Seaborn.Pairplot to plot the relationship between variables in the data set. I also used Seaborn.catplot to plot the relationship between total bill and tip amounts and the smoker variable in the Tips data set. I used pandas to analyse the relationship between some of the variables in the Tips data set and Seaborn to plot some different views of the relationship between these variables. I used the groupby function within pandas to group the total bill and tip amounts by some of the variables in the data set such as smoker, sex, day, time and day and time combined. This allowed me to calculate the mean and sum amounts broken out by these variables in order to see if any relationship exists between these variables and the bill and tip amounts. I used Seaborn to plot some of the findings in order to visualise the relationship between the variables. 

Some of the Seaborn plots I used in this section include:
* Seaborn.relplot()
* Seaborn.lmplot()
* Seaborn.catplot()
* Seaborn.barplot()
* Seaborn.boxplot()
* Seaborn.swarmplot()
* Seaborn.stripplot()
* Seaborn.violinplot()

**Relationship between variables- main findings:**
* My findings from this section:

    * **Is there a relationship between Smoker and total bill and tip amounts?:**
        * The mean bill is slightly higher for smoker and the tip amount is also slightly higher.
        * The mean party size is higher for smoker also. 
        * However, over the course of the 4 days non smoker accounted for higher bill and tip revenue. 
        * I conclude here that smoker/non smoker does not have a direct relationship with tip revenue but we could expect more people to seat in the non smoking section which will in turn generate higher tip revenue.
        * A waiter/waitress looking at this may prefer to work in the non smoking section.

    * **Is there a relationship between Sex and total bill and tip amounts?:**
        * The mean bill and tip amounts are larger for male.
        * The mean size is also slightly larger for male.
        * Over the 4 days the revenue generated for bills paid by male was much higher than female

    * **Is there a relationship between Day and total bill and tip amounts?**
        * The highest bill and tip revenue and most amount of customers in the restaurant are recorded on Saturday.
        * The lowest bill and tip revenue and least amount of customers was recorded on Friday.
        * I can see the day with the largest mean party size is Sunday with the smallest mean party size on Friday.
        * The largest mean bill amount is on Sunday with the smallest mean bill amount on Friday.
        * The day with the largest mean tip amount is also Sunday and the smallest tip amount is also Friday.
        * I conclude that day has an impact on tip amounts, as there are more parties likely to dine in the restaurant on Saturday and Sunday and thus higher tip revenue should be generated.

    * **Is there a relationship between Time and total bill and tip amounts?:**
        * Dinner yields much higher bill and tip revenue than lunch.
        * It must be noted dinner entries are recorded for 4 days and lunch for 2 days in the data set.
        * The mean bill, tip and party size are greater at dinner time than at lunch time.
        * Looking at this, a waiter may prefer to work at dinner time that at lunch time.

    * **Day and Time combined:**
        * The highest mean tip amount is Sunday at dinner time.
        * The lowest mean tip amount is Friday at lunch time.
        * The highest mean tip is recorded against the highest mean party size and highest mean bill amount.
        * The lowest mean tip is recorded against the lowest mean bill amount and the lowest mean party size.
        * This suggests me their is some relationship between party size and bill and tip amounts.
        * The restaurant appears to only open for lunch on Thursday and Friday.
        * Dinner on Thursday was extremely quiet with only 2 customers.
        * There were 219 customers for dinner on Saturday and 216 for dinner on Sunday.
        * Interestingly lunch time on Thursday was quiet busy compared with dinner time on Thursday whereas the opposite was the case on Friday with dinner being busier than lunch.
        * These statistics could be used by the restaurant to predict their busy and quiet times and plan accordingly.

# References 
**This section contains details on the references and research that went into compiling this project. These references are also listed throughout my jupyter notebook at the foot of each relevant section.**

**Jupyter lab** 
* Jupyter lab documentation - https://jupyterlab.readthedocs.io/en/stable/
* https://ipython-books.github.io/36-introducing-jupyterlab/
* https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906
* Youtube tutorials - https://www.youtube.com/watch?v=7wfPqAyYADY and https://www.youtube.com/watch?v=NXwP8pSOiB8
* How to change a cell to markdown: https://stackoverflow.com/questions/47787721/shortcut-key-for-changing-code-cell-to-markdown-cell-in-jupyter-notebook
* How to restart the kernel following instructions in lecture video: https://web.microsoftstream.com/video/31d34f49-725f-45bf-9e93-5f0594e69427?referrer=https:%2F%2Flearnonline.gmit.ie%2Fcourse%2Fview.php%3Fid%3D1127
* Centering text in a markdown cell: https://stackoverflow.com/questions/21722731/centering-headings-in-ipython-notebook?rq=1

**Section 1.1 References**
* pandas.read_csv documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html
* Blog post on reading in csv files with pandas: https://www.shanelynn.ie/python-pandas-read_csv-load-data-from-csv-files/
* Dataframe.head documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.head.html
* Dataframe.tail documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.tail.html
* Dataframe.describe(): https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.describe.html
* Percentile: https://www.statisticshowto.datasciencecentral.com/probability-and-statistics/percentiles-rank-range/
* Dataframe.shape documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.shape.html
* jupyter notebook pandas descriptive statistics example covered in lecture: https://nbviewer.jupyter.org/github/ianmcloughlin/jupyter-teaching-notebooks/blob/master/pandas-with-iris.ipynb
* Dataframe.loc documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.loc.html
* Dataframe.iloc documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.iloc.html
* Dataframe.mean documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.mean.html
* Dataframe.std() documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.std.html
* pandas.DataFrame.groupby: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.groupby.html
* pandas groupby: https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/
* astype(int): https://stackoverflow.com/questions/45451189/in-pandas-can-you-aggregate-by-mean-and-round-that-mean-to-the-nearest-int
* pandas sum: https://data36.com/pandas-tutorial-2-aggregation-and-grouping/
* Dataframe.sum(): https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sum.html
* pandas.groupby in action: https://data36.com/pandas-tutorial-2-aggregation-and-grouping/
* Blog post: https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/
* Dataframe.round(): https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.round.html
* df.info() documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.info.html
* Dataframe.astype documentation: https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.astype.html

**Section 1.2 References**
* Seaborn tutorial: https://seaborn.pydata.org/tutorial.html
* Seaborn documentation: https://seaborn.pydata.org/index.html
* Youtube: https://www.youtube.com/watch?v=TLdXM0A7SR8
* Seaborn.load_dataset documentation: https://seaborn.pydata.org/generated/seaborn.load_dataset.html
* Some further reading on loading in data set: https://www.datacamp.com/community/tutorials/seaborn-python-tutorial#load
* Seaborn.replot documentation: https://seaborn.pydata.org/generated/seaborn.relplot.html#seaborn.relplot
* Plotting in Seaborn: https://www.datacamp.com/community/tutorials/seaborn-python-tutorial#load
* The seaborn.distplot documentation: https://seaborn.pydata.org/generated/seaborn.distplot.html
* Plotting with distplot: https://pythonbasics.org/seaborn-distplot/
* The seaborn.countplot documentation: https://seaborn.pydata.org/generated/seaborn.countplot.html

**Section 2.1 and 2.2 References**
* What is Regression Analysis and Why Should I Use It?: https://www.surveygizmo.com/resources/blog/regression-analysis/
* A refresher on regression analysis: https://hbr.org/2015/11/a-refresher-on-regression-analysis
* Simple Linear Regression with NumPy- https://github.com/ianmcloughlin/jupyter-teaching-notebooks/raw/master/simple-linear-regression.ipynb
* Linear regression in Python: https://realpython.com/linear-regression-in-python/#regression
* Seaborn regression plots: https://www.geeksforgeeks.org/seaborn-regression-plots/
* Seaborn visualising linear relationships: https://seaborn.pydata.org/tutorial/regression.html
* Seaborn.lmplot: https://seaborn.pydata.org/generated/seaborn.lmplot.html#seaborn.lmplot
* Seaborn.regplot(): https://seaborn.pydata.org/generated/seaborn.regplot.html#seaborn.regplot

**Section 2.3 References:**
* Simple Linear Regression with NumPy - https://nbviewer.jupyter.org/github/ianmcloughlin/jupyter-teaching-notebooks/blob/master/simple-linear-regression.ipynb
* Introduction to linear regression: http://onlinestatbook.com/2/regression/intro.html
* Line of best fit: https://www.investopedia.com/terms/l/line-of-best-fit.asp
* Simple Linear Regression - Finding the equation of the line of best fit: http://www.ams.sunysb.edu/~zhu/ams571/Regression.pdf
* numpy.mean: https://docs.scipy.org/doc/numpy/reference/generated/numpy.mean.html
* numpy.polyfit documentation: https://docs.scipy.org/doc/numpy/reference/generated/numpy.polyfit.html.
* matplotlib.pyplot documentation: https://matplotlib.org/3.1.1/tutorials/introductory/pyplot.html
* matplotlib.pyplot.plot(): https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.plot.html
* matplotlib.pyplot.legend: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.legend.html
* matplotlib.pyplot.ylabel: https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.ylabel.html
* matplotlib.pyplot.xlabel: https://matplotlib.org/3.1.0/tutorials/introductory/pyplot.html
* matplotlib.pyplot.show() https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.show.html
* numpy.corrcoef: https://docs.scipy.org/doc/numpy/reference/generated/numpy.corrcoef.html
* Correlation in Python: http://benalexkeen.com/correlation-in-python/

**Section 2.4 References:**
* PYTHON MACHINE LEARNING EXAMPLE – LINEAR REGRESSION: https://devarea.com/python-machine-learning-example-linear-regression/#.XdZkSej7TIU
* Ordinary least squares: https://scikit-learn.org/stable/modules/linear_model.html#ordinary-least-squares
* scikit learn.linear_model.LinearRegression: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html
* numpy.polyfit documentation: https://docs.scipy.org/doc/numpy/reference/generated/numpy.polyfit.html
* Beginner's guide to regression in Python with Scikit learn: https://towardsdatascience.com/a-beginners-guide-to-linear-regression-in-python-with-scikit-learn-83a8f7ae2b4f
* How to run linear regression in python scikit learn: https://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/
* Linear Regression — Python Implementation: https://towardsdatascience.com/linear-regression-python-implementation-ae0d95348ac4
* .fit: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression.fit
* .score: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression.score
* Interpreting the Intercept in a Regression Model: https://www.theanalysisfactor.com/interpreting-the-intercept-in-a-regression-model/

**Section 3.1 References**
* The documentation for seaborn.pairplot is here: https://seaborn.pydata.org/generated/seaborn.pairplot.html
* I read about seaborn.pairplot on the following blog post: https://towardsdatascience.com/visualizing-data-with-pair-plots-in-python-f228cf529166
* Seaborn pairplot: https://pythonbasics.org/seaborn_pairplot/

**Section 3.2 References**
* Seaborn.catplot documentation: https://seaborn.pydata.org/generated/seaborn.catplot.html
* Swarmplot(): https://seaborn.pydata.org/generated/seaborn.swarmplot.html#seaborn.swarmplot

**Section 3.3 References**
* pandas sum: https://data36.com/pandas-tutorial-2-aggregation-and-grouping/
* Dataframe.sum(): https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.sum.html
* pandas.groupby in action: https://data36.com/pandas-tutorial-2-aggregation-and-grouping/
* Blog post: https://www.shanelynn.ie/summarising-aggregation-and-grouping-data-in-python-pandas/
* Dataframe.round(): https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.round.html
* Dataframe.groupby.mean() - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.core.groupby.GroupBy.mean.html
* Dataframe.groupby.sum() - https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.core.groupby.GroupBy.sum.html
* Seaborn.swarmplot(): https://seaborn.pydata.org/generated/seaborn.swarmplot.html#seaborn.swarmplot
* Seaborn.boxplot(): https://seaborn.pydata.org/generated/seaborn.boxplot.html#seaborn.boxplot
* Seaborn.stripplot(): https://seaborn.pydata.org/generated/seaborn.stripplot.html#seaborn.stripplot
* Seaborn.violinplot documentation: https://seaborn.pydata.org/generated/seaborn.violinplot.html#seaborn.violinplot
* Blog post: https://towardsdatascience.com/analyze-the-data-through-data-visualization-using-seaborn-255e1cd3948e