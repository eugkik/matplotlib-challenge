# matplotlib-challenge

The 'MatPlotLib' Jupyter Notebook will read the 'Mouse_metadata.csv' and 'Study_results.csv' files and create a merged dataframe.

The number of unique mice and duplicate mice ID that shows up for Mouse ID and Timepoint will be found.  All study data for duplicate mice will be displayed and removed from the dataframe.  The number of remaining unique mice will be found.

A summary statics dataframe will be created and displayed with mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.  The same information will also be found using the aggregation method.

Bar charts create by Pandas and pyplot will be created and displayed for the total number of timepoints for all mice tested with each drug regimen.

Bar charts create by Pandas and pyplot will be created and displayed showing the distribution of female vs male mice.

The greatest timepoint for each mouse will be found (alternate method also included).  The final tumor volume of each mouse across the drug treatments Capomulin, Ramicane, Infubinol, and Ceftamin will be displayed in a box and whisker chart.  Outliers for each treatment will be output and also identified on the chart as red diamonds.

A line plot of tumor volume vs timepoint for mouse b128, treated with Capomulin, will be plotted.

A scatter plot of average tumor volume vs mouse weight for the Capomulin regimen will be plotted.

The correlation coefficient for mouse weight and average tumor volume for Capomulin will be calculated and displayed.

The linear regression model will be calculated and displayed with the Capomulin regimen scatter plot.