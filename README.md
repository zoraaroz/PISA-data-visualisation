# PISA Data Exploration
## by Zora Schärer


## Dataset

This project analyses the PISA data from 2012. The dataset contains data of about 485.000 students from 68 countries. There are variables describing the students attitude towards school, personal motivation, family background, social and financial status as well as their school performance in three different areas: maths, reading and science.

At first I chose a subset of variables that I was interested in. All data columns were in string format, so I changed the numerical variables to floats. Furthermore I defined an ordered categorical type for the parents education variable. Later during the exploration I added a further categorical variable based on the performance of students with the levels high, mid and low performance.

## Summary of Findings

The measures for the school performance for each area are the so called plausible values (PVs). These are normally distributed. Looking at the correlation between the numerical variables of interest revealed that there were high correlations between the PVs but only low correlations between the PVs and most of the chosen independent variables. The only relationship with a noteable correlation was between the PVs and the economic, social and cultural status of students. There were some interesting (low) correlations between independent variables though.

A scatterplot for the PVs and the learning times (with logarithmic axes for the learning times) showed that the answers were given in multiples of 15 minutes at the lower end of the scale while they were more distributed towards longer learning times.

Furthermore I found that the school performance of students increases with increasing level of their parents' education. I found it surprising to see in a plot faceted by performance level that this effect was limited to the students with high PVs and most clear for reading and science.

Ordering the countries by PV for each area showed that the order of countries was quite similar for the three areas. Interestingly, the four countries at the high end of the scale had best values in maths while the countries at the low end of the scale had worst values in maths.

## Key Insights for Presentation

Have a look at the presentation.slides.html for a nice presentation of my findings.

I chose to concentrate on four key insights/plots:

* Distribution of dependent variables
* Correlation matrix
* Country ranking
    * I added a grid here for better readability
* PVs vs. parents education
    * I separated this into two slides, one for the overall plot and one for the plot separated by performance category
    * I changed the colors for the areas in the separated plots to a differential rather than a sequential color scheme (matching the colors of the country ranking plot)
