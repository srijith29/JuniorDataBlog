#JuniorDataBlog

## Introduction
Junior data blog explores the StackOverFlow survey 2019 to find out inferences on Junior data professionals.
The main 3 questions the blog tries to answer are 
1. Role of the junior data professionals.
2. Time spent by these professionals in a typical working week.
3. List of skills possessed by top earners.

## Data
The data set used has been obtained from the StackOverFlow site and is available at https://insights.stackoverflow.com/survey/

## Data Preprocessing
The dataset is filtered to represent Junior Data Professionals. A junior data porfessional is defined as some one with 
less that 1 year of professional coding experience and has the string 'Data' in their response to the question what kind of developer type are you.
For the variable 'CompTotal' that is total compensation there were 184 NA values present and there were unreal responses that amounted
to 1 billion. Because of these outliers the median of the total compensation attribute was used to replace the NA values.
There were responses where multiple responses were chosen by 1 respondent like in the case of 'devtype'. Some has responded that they are 
back end developer and a data scientist. In such a case both the types (back end developer and data scientist) are counted once each. 





