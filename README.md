# HW06: Generating reproducible social science research

## Analysis of Traumatic Brain Injury (TBI) 

### This project aims to explore the following aspects of Traumatic Brain Injury (TBI):

* The distribution of TBI severity (mild, moderate, severe, penetrating) in different branches of the military.
* The annual trend in the number of deaths due to different injury mechanisms causing TBI.
* The primary causes of TBI and how they affect different age groups.

### Datasets

* tbi_age.csv: This dataset provides information about TBI cases in different age groups for the year 2014. The variables include age group, type of measure, cause of the injury, estimated number of cases, and estimated rate of TBI per 100,000 people.
* tbi_year.csv: This dataset provides information about TBI cases over different years. The variables include the cause of the injury, type of measure, year of observation, estimated number of cases, and estimated rate of TBI per 100,000 people in the year of observation.
* tbi_military.csv: This dataset provides information about TBI cases in different branches and components of the military. The variables include the branch of the military, the component of the military (active, guard, reserve), the severity or type of TBI, the number of diagnosed cases, and the year of observation.

### Scripts in this repository

* Data analysis: TBI.Rmd. 
* Report: TBI_Report.Rmd
* You can reproduce the results by following the steps outlined in the code files: TBI.Rmd. After executing these scripts with the provided data, you will generate the figures shown in the report: TBI_Report.md.

### Additional packages

You need to install some additional packages before executing the files. 

```
install.packages("gridExtra")
install.packages("ggtext")
```

### Any other relevant information

N/A

### Reflections

* Working on this project was both challenging and rewarding. One of the main challenges was understanding the data and how it could be used to answer the research questions. However, the process of exploring the data, visualizing it, and uncovering insights was enjoyable and fulfilling.

* One challenge was formulating the research questions. It was crucial to define questions that were both interesting and feasible to answer with the available data. This required a good understanding of the data as well as the subject matter. I found it useful to do some background reading on traumatic brain injury to help formulate the questions. I enjoyed the process of working with real-world data and applying the data analysis skills I've learned. The satisfaction of uncovering insights from the data and answering the research questions was well worth the effort. 
