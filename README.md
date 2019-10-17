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
The official Seaborn tutorial is here: https://seaborn.pydata.org/index.html and the official Seaborn tutorial is here: https://seaborn.pydata.org/index.html. 
"Seaborn aims to make visualization a central part of exploring and understanding data. Its dataset-oriented plotting functions operate on dataframes and arrays containing whole datasets and internally perform the necessary semantic mapping and statistical aggregation to produce informative plots." - Taken from the official Seaborn documentation - https://seaborn.pydata.org/introduction.html

## What is the Tips dataset?


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