# ISA616Repo

In this analysis, I create a stepwise multiple linear regression model that uses physiochemical properties of wine to predict the wine quality score. 
This model will allow the product design team at Wine Inc. that creates new wine variants to better understand what levels of physiochemical properties 
lead to a better wine quality score for their variants of the Portuguese “Vinho Verde” wine.

For this analysis, we use R version 3.6.1. Further information regarding the session information and packages used can be seen in the R Markdown or HTML file. 

We access the wine quality data from the University of California, Irvine’s Machine Learning Repository. 
There are two datasets related to red and white variants of the Portuguese “Vinho Verde” wine. 
One dataset is for the white variants, and one is for the red variants. 
We access these datasets directly via the curl package, but the link to manually download these two datasets is below in case there are any issues:
https://archive.ics.uci.edu/ml/datasets/wine+quality

No extra files are needed in order to run this analysis. But, in case the links used to access the data break, I have provided two csv files for the red and white wine data that can be used.
