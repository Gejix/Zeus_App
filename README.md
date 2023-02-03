# Zeus App

<img src="/Source/Zeus.JPG" alt="App interface" width="1000" height="300">

## Description 
Zeus application is a multi-statistical app that displays the graphs of Police stop and search reports from the year 2020 to 2022 and the Covid19 cases that OCCURRED IN 2020. 

## Installations
Before going ahead to run the program, the below libraries and packages must be installed on your machhine.
- Install python (https://www.python.org/downloads/)
- Install python in your machine
- Install Anaconda (https://docs.anaconda.com/anaconda/install/index.html)
- Lunch Jupyter Lab
- Install the following libraries
    *   pandas:            *pip install pandas*
    *   requests:          *pip install request*
    *   matplotlib:        *pip install matplotlib*
    *   datetime:          *pip install datetime*

| Files | Description          |
| --------- | ------------------- |
| Documentation | Folder that contains the black box testing and Report of the GUI |
| Source | Folder that contains the assets for the project |
| Covid_script.ipynb | Script that plots the various Covid19 Data analysis |
| GUI ICA.ipynb| Script to run the graphical user interface for the Zeus app|
| Stop_and_search_script.ipynb | Script that plots the various Police reports from 2020 till date|
| test_file.ipynb | Unit testing file|

## Code Execution
There are three different files in the project. As pointed out earlier, these files are the Covid script and the Start and stop script, which is used to view the Data analysis of the various sets. All are powered by Jupyter lab or notebook and should be run in such. The third file is the GUI script that contains the graphic user in their face code for the user. It generates a page that the user uses to interact with, to plot the expected graphs of the data analysis.

### GUI_ICA
The main app is ran from this terminal

### COVID_19
To visualize the COVID 19 dataset, click on the Covid 19 report button 
*   It immediately plots and returns the visualizations for the different charts plots.
The charts plotted are;
    * Daily total number of cases from July to November
    * Areas with the highest number of cases on the 2020-03-20
    * Daily total number of cases in 2020
    * Comparison of total cases in London and Liverpool

### Stop and Search
To visualize the Data analysis of the Stop and Search API data set, click on the  Police report button
*   Pick the location of the Police Force from the drop-down.
*   Select the year of interested stop and search between 2020 to 2021 from the drop-down
*   Select the month of interest, i.e. 1 for January, 7 for July, from the drop-down
*   The Stop and Search Button is clicked to display the visual which appears in the Jupyter notebook
*   The text box then shows the analysis of the supposed day, a display of the number of people stopped and searched during the period under review

### Click on Close to exit the GUI 

##  Unit test

Three unit tests were needed to run this project. To run the test;

*   Run the test_file.ipynb file
*   Execute the code using Jupyter notebook.
*   The code runs successfully, returning OK on the three tests that ran

## Authors
-	`Gerald Juwah` geraldjuwah@gmail.com
