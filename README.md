
# Data Analysis on StackOverFlow Developer Survey 2017 Dataset
I have used CRISP-DM process during this analysis. 
1. Business Understanding - Started analysis with posed questions in mind.
2. Data Understanding - To better understand the data, I started going through the dataset and noted points as how to use it for my analysis. For example: which columns will be helpful to answer a particular questions?
3. Prepare Data - At various points, I have to do data wrangling and perform data transformation to achieve the results. Keeping DRY techniques in mind, I have also created a function to draw plotly barchart as this code was repeating often.
4. Model Data - My analysis does not involve modeling step. I might add this in my future work.
5. Results - I am using visualizations like barchart and piecharts to convey my findings, also added result statements at the end of every visualization for easy understanding of thought process.
6. Deploy - I am not deploying this code anywhere right now. For now, it is available in jupyter notebook form only.


 


### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing) 
<!--3. [File Descriptions](#files)
4. [Results](#results) -->

## Installation <a name="installation"></a>

Install plotly first, after that there should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

1. How other developers suggested breaking into the field (what education to pursue)?
2. What factors about an individual contributed to salary?
3. What was the state of bootcamps for assisting individuals with breaking into developer roles?
4. How were bootcamps assisting with increasing diversity in tech careers?
5. According to EmploymentStatus, which group has the highest average Career satisfaction?


## File Descriptions <a name="files"></a>

There is one notebook available here to showcase work related to the above questions.  This notebook is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  
Data files : [Download](https://www.kaggle.com/stackoverflow/so-survey-2017#survey_results_public.csv)


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@monika.bagyal/how-to-perform-data-analysis-using-the-crisp-dm-approach-201708f220b2).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 
