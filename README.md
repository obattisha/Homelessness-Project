# Homelessness-Repo


##Project for CMSC/STAT 118 - Fall Quarter 2019 (due November 12)
This is not a group project. You may discuss the project with other students but you should code and write the report independently. You should acknowledge any help in writing. The score will be based on:

clarity an soundness of the arguments and conclusions;
use of data to back up arguments and analysis quality;
insightfulness of the results;
quality of the data vizualization, summaries used, and overall presentation.
The project is inspired by the current Fall Data Challenge from the American Statistical Association. You can find information about it here: https://thisisstatistics.org/falldatachallenge/

The goal of the ASA Data challenge is to use "statistical and data visualization skills [...] to help find ways to reduce and resolve the homelessness crisis, using HUD’s 2018 Point-in-Time Estimates of Homelessness in the U.S. dataset":

https://www.hudexchange.info/resource/5783/2018-ahar-part-1-pit-estimates-of-homelessness-in-the-us/

The goal of this project is gain insight on homelessness using the tools you have learned so far in this class.

The Data
You can use any data you can find to answer the questions below (note that the website for the ASA challenge contains links to various datasets), but you need to specify the provenance of the data in your report.

One interesting question is on the city-level homelessness estimates, and we will begin by using data corresponding to "Continuums of Care" (CoC), which are local planning bodies responsible for coordinating the full range of homelessness services in a geographic area, which may cover a city, county, metropolitan area, or an entire state." To this end, we have downloaded the files 2007 - 2018 Point-in-Time Estimates by CoC and 2007 - 2018 Housing Inventory Count by CoC from the linked resources page. These are Excel files with separate tabs for each year - to make it easier on you, we've aggregated all the years into one file and selected some important columns.

We saved the results into files that can be downloaded from Canvas. If some of the columns/data require more information, you can find it in the files available from HUD. Note that not all columns of data were available in all years.

You should go back to the original datasets and import more data if they are relevant for your analyses.

The next cell that contains code that will allow you to read the data into a tables called "pit_table" and "beds_table". It also shows the first 10 rows.
##The Assignment
Report on your findings on homelessness. Can you suggest interventions or policies for helping solve homelessness? You must submit two files:
The Jupyter Notebook that contains all the code you use for the analysis. You do not need to submit data you used, but just indicate how you obtained it in the Notebook.

A PDF report of your findings. This report should be at most 4 pages long, with at most two pages of text. Use data visualization and data summaries to justify your conclusions.

The report should answer at the minimum the following questions:

A. Are there any temporal patterns in the number of homeless people in Chicago and in Los Angeles?

B. Are there any spatial patterns in the number of homeless people? (Northern versus Southern states, Midwest versus the Coasts)

C. Are there any patterns in the bed inventory data?

D. How does beds availability affect homelessness?

E. What are possible ways to reduce and resolve the homelessness crisis?
