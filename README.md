# matplotlib-challenge
## monu-virt-data-11-2021-u-c course Week 5 Assignment

For this assignment, we had to create multiple visualisations for a dataset that was compiled to compare performance of several drug regimens on their effectiveness to treat SCC tumor growth in mice.

First we merged two datasets, one being about the individual mice and the second being the related study information. This data was checked for duplicates, then cleaned to remove any duplicates that occurred.

A summary statistics table was then created, to easily see the mean, median, variance, standard deviation and SEM values of the Tumor Volumes across the different Drug Regimens. This was found by grouping the data by the drug first, then calculating the values.

A bar chart was then created, to visualise the total number of Timepoints for all mice, by the drug they were given. The bar chart was output in both matplotlib and pandas syntax.

A pie chart showing distribution of the sex of the mice was then created, the syntax of matplotlib and pandas were used to create the same chart twice.

We then compared 4 of the drugs, Capomulin, Ramicane, Infubinol, and Ceftamin, and found their corresponding first, second and third quartile values, their interquartile ranges, and upper and lower boundaries to test for any outliers in the data. This was visualised with a Box and Whisker plot.

We then selected a mouse that was treated with Capomulin, s185, and plotted the size of their tumor over time.

Finally, we produced a scatterplot, comparing the weight and average tumor volume for mice treated with Capomulin. Further we found the correlation coefficient as well as the linear regression model of this data, plotting the regression over our original scatterplot.

# Observations and Insights 

### Observation 1
 - From our line plot, we can see that mouse s185's tumor decresed in volume over time when being treated with Capomulin
 
### Observation 2
 - From our summary statistics table, it can be seen that Ramicane has the lowest values across all summarised values (mean,median,variance,standard deviation and SEM), this could indicate a high effectiveness for treating SCC tumor growth
 
### Observation 3
 - Due to the positive correlation coefficient between Weight and Tumor Volume in Capomulin treated mice, we can say that heavier mice tend to have larger tumor volumes
