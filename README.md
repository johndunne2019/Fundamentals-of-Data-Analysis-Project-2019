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

## What is the Tips dataset?

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

## References 
**This section contains details on the references and research that went into compiling this project.**

**Jupyter lab** 
* Jupyter lab documentation - https://jupyterlab.readthedocs.io/en/stable/
* https://ipython-books.github.io/36-introducing-jupyterlab/
* https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906
* Youtube tutorials - https://www.youtube.com/watch?v=7wfPqAyYADY and https://www.youtube.com/watch?v=NXwP8pSOiB8
* How to change a cell to markdown: https://stackoverflow.com/questions/47787721/shortcut-key-for-changing-code-cell-to-markdown-cell-in-jupyter-notebook
* How to restart the kernel following instructions in lecture video: https://web.microsoftstream.com/video/31d34f49-725f-45bf-9e93-5f0594e69427?referrer=https:%2F%2Flearnonline.gmit.ie%2Fcourse%2Fview.php%3Fid%3D1127

**Seaborn**
* Seaborn tutorial: https://seaborn.pydata.org/tutorial.html
* Seaborn documentation: https://seaborn.pydata.org/index.html
* Youtube: https://www.youtube.com/watch?v=TLdXM0A7SR8

**Tips Data set**
* Repository from which seaborn.load reads the data set from: https://github.com/mwaskom/seaborn-data
* Direct link to the data set csv file: https://github.com/mwaskom/seaborn-data/blob/master/tips.csv
* Seaborn.load https://stackoverflow.com/questions/30336324/seaborn-load-dataset
* Background of the Tips dataset: https://www.kaggle.com/ranjeetjain3/seaborn-tips-dataset

**pandas - Python Data Analysis Library**
* pandas documentation: https://pandas.pydata.org/
* 10 minutes to pandas: https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html
* Wes McKinney - 10-minute tour of pandas - https://www.youtube.com/watch?v=_T8LGqJtuGc
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