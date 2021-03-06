# Matplotlib_Challenge

A burgeoning pharmaceutical company based out of San Diego, Pymaceuticals specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In the most recent animal study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

## Prepwork

* Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

## Summarize

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and Standard Error of the Mean of the tumor volume for each drug regimen.

## Analyze
* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the total number of measurements taken for each treatment regimen throughout the course of the study. Include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study. Include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 

* Calculate the quartiles and interquartile range and quantitatively determine if there are any potential outliers across all four treatment regimens. 

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style. Include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

  **Hint**: All four box plots should be within the same figure. Use this [Matplotlib documentation page](https://matplotlib.org/gallery/pyplots/boxplot_demo_pyplot.html#sphx-glr-gallery-pyplots-boxplot-demo-pyplot-py) for help with changing the style of the outliers.

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse. Include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen. Include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

* Calculate the correlation coefficient (https://www.youtube.com/watch?v=xZ_z8KWkhXE) and linear regression model (https://www.youtube.com/watch?v=nk2CQITm_eo) between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot. Include properties such as: plot titles, axis labels, legend labels, _x_-axis and _y_-axis limits, etc.

## Document Conclusions
* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
