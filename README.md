# UdacityDataScience_Project1

**Table of Contents**

  1.	Installation
  2.	Project Motivation
  3.	File Descriptions
  4.	Results
  5.	Licensing, Authors, and Acknowledgements

**Installation**

Anaconda Navigator V.1.10.0 was utilised, with the code being written using Jupyter Notebook V.6.1.4. Python version 3 was used. There were no further installations required, beyond standard packages provided within Python versions 3.*. These were: Numpy, Pandas, Seaborn and Matplotlib  

**Project Motivation**

This Project is part of Lesson 1 of the Udacity Nanodegree, where the aim was to identify and analyse 3-5 business questions using the Stack Overflow 2017 Survey data. For this analyses I chose to focus on 3 questions relating to Satisfaction of Respondents and influence that Parents have on their children’s careers:

  1.	Firstly, are Respondents to the Survey looking for new Job opportunities?

  2.	What are the different ways of working, measured though how often someone is working from home, and does this flexible working bring Satisfaction? 

  3.	Does the Education level of a parent have any bearing on the education level of the Respondent?

**File Descriptions**

There is only one notebook for this analysis, it is a self-contained notebook which will produce the output for each of the 3 stated questions. The notebook has been separated into sections. At the start of the Notebook the business questions have been stated along with how they will be approached/ answered with the data provided. After each question cells have been used to provide interpretation of the output.  

**Results**

Cells within the Notebook provide some interpretation of the results, the main findings however, can be found at the following [Medium post](https://grant25.medium.com/looking-for-a-new-job-ask-your-parents-ec6b723e2d82). A summary is also provided below:

In summary, descriptive statistics were used to analyse this data with bar charts and a heat map being used to visualise the findings. Means and Medians were also reported. Median was chosen for the Satisfation measures to give a representation of what the majority of respondents scored for these questions. Imputation of missing data was also preformed this was to provide a 'Missing' level for reporting, and to confirm if differences observed between groups were genuine.

  1.	Firstly, are Respondents to the Survey looking for new Job opportunities? It was found that 13% (4,371 respondents) were seeking a new role. 62% (20,729  respondents) are       not actively looking for a new role, but are open to new opportunities. Those looking for new opportunites spend over 8 hours a week doing this, and are also paid the           least when compared to those not looking for new job opportunities.
 
  2.  Looking at whether the respondent has home or flexible working it was found that 30% of respondents indicated that they work from home 'A few days each month' and 27.2%
      responding that they 'Never' work from home. Respondents that spent nearly half their time working from home spent almost 5 hours a week looking for a new job, compared to       3–3.5 hours for those that never work from home. Median Satisfaction was consistient across all work from home groups. 
      
  3.  Considering education level of the parent and respondent attainment. Where a parent had higher education then 78.4% of respondents also had higher education, whilst 20.7%       of respondents did not. Conversely, where the parent has no higher education, the percentages of respondent level of education are closer. Where the parent did not have
      higher education 56% of respondents did have a higher education whilst 43.1% did not.
     
Additional analyses were considered for this Project but were not taken forward. These included: Investigating the Importance/Benefits field and link to Satisfaction, as well as developing a model to predict time spent at home looking for new roles

**Licensing, Authors, Acknowledgements**

Data was provided by Stack Overflow, and sourced from Kaggle at the following link: [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data). Data licensing is described as ‘Open Database’.

Function ‘higher_ed’ was taken from Udacity, DataScience Nanodegree (Introduction to DataScience, Lesson 2 - S12) and modified to answer Question 3
