# **Matplotlib Challenge: The Power of Plots**

![](Pymaceuticals/data/Laboratory.jpg)

# Background
Pymaceuticals Inc. began its most recent project in screening for potential treatments for Squamous Cell Carcinoma (SCC) which is a common occuring form of skin cancer.

The complete <a href="Pymaceuticals/data/Mouse_metadata.csv">dataset</a> from the most recent animal study is provided. In this study, 249 mice identified with SCC tumour growth were treated with various drug regimens. The purpose of the study is to compare the performance of the drug "Capomulin with the other treatments.

The task as the senior data analyst is to generate all the tables and figures needed for the technical report of the study.

# Analysis
Cleaning the data: checking the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Generate a summary statistics table tumour volume for each drug regimen.

* Using Pandas's DataFrame.plot() and Matplotlib's pyplot:
    *  Generate bar charts that shows the number of total mice for each treatment regimen throughout the course of the study.

    * Generate pie plots that shows the distribution of female or male mice in the study.


* Calculate the final tumour volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

* Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumour volume for all four treatment regimens and highlight any potential outliers in the plot by changing their colour and style.


* Select a mouse that was treated with Capomulin and generate a line plot of tumour volume vs. time point for that mouse.

* Generate a scatter plot of mouse weight versus average tumour volume for the Capomulin treatment regimen.

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumour volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

# Conclusions
Based on the generated tables and figures, I am able to draw some conclusions about the study which can be found <a href="Pymaceuticals/Conclusion.txt">here.</a>