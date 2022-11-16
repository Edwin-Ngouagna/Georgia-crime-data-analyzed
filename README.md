# Georgia-crime-data-analyzed

In this project, I analyzed the Georgia crime dataset downloaded from Georgia - Uniform Crime Reporting – FBI (https://ucr.fbi.gov/crime-in-the-u.s/2018/crime-in-the-u.s.-2018/tables/table-8/table-8-state-cuts/georgia.xls)
Note that the dataset is subject to updates, the results you will have may not be exactly what  I present here.
In analysis, I sought to know the:
1.	If there is a linear relationship between population (specifically where population ≤150,000) and murder rate in Georgia.

Hypothesis
Ho – There are no significant linear relationship between population (specifically where population ≤150,000) and murder rate in Georgia.

Analysis
The data was analyzed using R statistical software version 4.2.1.
First we imported the data into R, 
Missing value analysis
Filter the data
Rename some variables (dplyr package)
Data exploration to fully understand the data (glimpse using the EpiR package)
Check for normality (Shapiro Wilk test and histograms)
Check for linearity 
Data transformation using the mutate function
Simple linear regression
Interpretation

