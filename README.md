#JuniorDataBlog

## Introduction
The motivation for this blog is my personal experience of being a newcomer in the field of DataScience. Every one of us might be overwhelmed with the scale of requirements out there.  This blog tries to answer some
common questions anybody starting in this field could have. Fortunately for us stackoverflow, the go-to place for anything technical conducts a survey every year and collects data from its users. This is a comprehensive survey consisting of programmers, data scientists,
testers, and other technical people. The original survey has been reduced to responses that had a 'Data' title in their
designation. More about this in the data preprocessing section.

In short Junior data blog explores the StackOverFlow survey 2019 to find out inferences on Junior data professionals.
The main 3 questions the blog tries to answer are 
1. Role of the junior data professionals.
2. Time spent by these professionals in a typical working week.
3. List of skills possessed by top earners.

## Data 
The data set used has been obtained from the StackOverFlow site and is available at https://insights.stackoverflow.com/survey/. This is a 
survey dataset with 88883 responses for 85 questions from respondents. This include questions like "DevType" implying job title, 'TotalComp'- Total compensation etc. A pdf file 'so_survey_2019.pdf' is provided which is the pdf version of the questionnaire. 

## Data Preprocessing
The dataset is filtered to represent Junior Data Professionals. A junior data porfessional is defined as some one with 
less that 1 year of professional coding experience and has the string 'Data' in their response to the question "Which of the following describe you?". This is coded as 'DevType' in the data file.

## Outliers
For the variable 'CompTotal' that is total compensation there were 184 NA values present and there were unreal responses that amounted
to 1 billion. Because of these outliers the median of the total compensation attribute was used to replace the NA values.
There were responses where multiple responses were chosen by 1 respondent like in the case of 'devtype'. Some has responded that they are 
back end developer and a data scientist. In such a case both the types (back end developer and data scientist) are counted once each. 





