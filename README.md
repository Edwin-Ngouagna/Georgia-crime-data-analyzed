# Georgia-crime-data-analyzed

In this project, I analyzed the Georgia crime dataset downloaded from Georgia - Uniform Crime Reporting – FBI (https://ucr.fbi.gov/crime-in-the-u.s/2018/crime-in-the-u.s.-2018/tables/table-8/table-8-state-cuts/georgia.xls) <br>
Note that the dataset is subject to updates, the results you will have may not be exactly what  I present here.
In analysis, I sought to know the:<br>
1.	If there is a linear relationship between population (specifically where population ≤150,000) and murder rate in Georgia.<br>

Hypothesis<br>
Ho – There is no significant linear relationship between population (specifically where population ≤150,000) and murder rate in Georgia.<br>

Analysis<br>
The data was analyzed using R statistical software version 4.2.1.<br>
First we imported the data into R, <br>
Missing value analysis<br>
Filter the data<br>
Rename some variables (dplyr package)<br>
Data exploration to fully understand the data (glimpse using the EpiR package)<br>
Check for normality (Shapiro Wilk test and histograms)<br>
Check for linearity <br>
Data transformation using the mutate function<br>
Simple linear regression<br>
Interpretation<br>

