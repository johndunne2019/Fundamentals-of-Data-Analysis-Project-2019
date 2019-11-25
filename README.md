# Fundamentals-of-Data-Analysis-Project-2019

This repository contains my project 2019 for the module Fundamentals of Data Analysis at GMIT. See here for the instructions: https://github.com/ianmcloughlin/project-2019-fundda/raw/master/project.pdf. References and resources I used in compiling this project are listed in the references section at the foot of this Readme file.

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

## Plan for completing this assessment
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

## Python packages I used in my analysis of the Tips dataset

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
The official Seaborn documentation is here: https://seaborn.pydata.org/index.html and the official Seaborn tutorial is here: https://seaborn.pydata.org/index.html. 

"Seaborn aims to make visualization a central part of exploring and understanding data. Its dataset-oriented plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots." - Taken from the official Seaborn documentation - https://seaborn.pydata.org/introduction.html

## pandas
Python Data Analysis Library is a Python package than can be used to analyse data sets such as the Tips data set. I used pandas to do some basic descriptive statistics on the Tips data set. pandas can deal with both strings and floating point numbers and so is a good package to use to analyse the Tips data set. The official pandas documentation is located here: https://pandas.pydata.org/ and there is a useful tutorial here: 10 minutes to pandas: https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html. 

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

## Scikit learn

## matplotlib


## My jupyter lab notebook 

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

Quote taken from: https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset

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

* pandas

I read in the data set with pandas and returned some descriptive statistics about the data set using some functions within the pandas library.

* Seaborn

I used Seaborn to read in the data set and output some plots based on the data set and I explained how the different types of plots work and why they would be used in analysing a data set.

##  Section 2: Regression

In this section I discussed and analysed whether there is a relationship between the total bill and tip amount. I did this by using Seaborn to plot the regression line with the lmplot() and regplot() functions. I also added a section to the jupyter notebook looking at simple linear regression and the best fit line. The slope, intercept and R Squared values of a best fit line can be calculated using numpy.polyfit or by using a calculation that I have explained in the notebook. I added another section looking at how Scikit learn can be used to calculate the slope, intercept and R Squared values of the best fit line. The results of this regression analysis showed there is a relationship between total bill and tip amounts. The R-squared value of the best fit line is: 0.45661658635167635 which shows that 45.6% of the data is accounted for by the regression model. This shows that their is a reasonably strong relationship between total bill and tip amount but that other factors may also play their part in determining tip amount etc.

## Section 3: Relationship between the variables in the Tips data set

In this section I analysed the relationship between some of the variables in the data set. I used Seaborn.Pairplot to plot the relationship between variables in a data set. 
 
 TO BE FINISHED LATER




## References 
**This section contains details on the references and research that went into compiling this project.**

**Jupyter lab** 
* Jupyter lab documentation - https://jupyterlab.readthedocs.io/en/stable/
* https://ipython-books.github.io/36-introducing-jupyterlab/
* https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906
* Youtube tutorials - https://www.youtube.com/watch?v=7wfPqAyYADY and https://www.youtube.com/watch?v=NXwP8pSOiB8
* How to change a cell to markdown: https://stackoverflow.com/questions/47787721/shortcut-key-for-changing-code-cell-to-markdown-cell-in-jupyter-notebook
* How to restart the kernel following instructions in lecture video: https://web.microsoftstream.com/video/31d34f49-725f-45bf-9e93-5f0594e69427?referrer=https:%2F%2Flearnonline.gmit.ie%2Fcourse%2Fview.php%3Fid%3D1127
* Centering text in a markdown cell: https://stackoverflow.com/questions/21722731/centering-headings-in-ipython-notebook?rq=1