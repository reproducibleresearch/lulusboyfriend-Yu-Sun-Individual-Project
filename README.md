## BST 270 Individual Project

#### Author: Yu Sun
#### Email: ysun1@hsph.harvard.edu
#### last Update: 2021-01-25


##### **Purpose**
The purpose of this project is to evaluate the reproducibility of the visulaization resutls from [New York Times](https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html) about COVID-19 by utilizing the data set that provided to reproduce specific figures and tables, which were provided in this repository (nyt1.png, nyt2.png, and nyt3.png); more specifically, this project will recreate one figure and two tables of COVID-19 for January 17th, 2021.

##### **Data Set**
There are two data sets for this project: [us_counties.csv](https://github.com/nytimes/covid-19-data) and [all-states-history.csv](https://covidtracking.com/data); there are also provided in this repository, which were accessed on January 25th, 2021 and this project was designed to reproduce the results on January 17th, 2021.

##### **Code and Results**
The code and detailed guideline of the process of reproduction were provided in this repository as a Rmarkdown file named project.rmd; furthermore, the results were generated as project.html and project.pdf.

##### **Software and Version**
To reproduce this project, users need to download the original Rmarkdown file and the two data sets from this repositroy. Additionally, the users need to install [R (Version 4.0.2 or above)](https://www.r-project.org/) and [R Studio](https://rstudio.com/products/rstudio/download/) to run the Rmarkdown file and reproduce the results from this project. On the other head, some specific packages (tidyverse, lubridate, zoo, knitr) were required for this project and they should be install before running the code. [How to install packages on R](https://www.datacamp.com/community/tutorials/r-packages-guide)