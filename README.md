# Basic PyPlot Examples
This repository contains well-commented, stand-alone scripts that display some basic PyPlot plotting techniques. The plots are static and 2D.

## Functions used
The scripts here make use of some functions described in the [PyPlot API](http://matplotlib.org/api/pyplot_api.html).

#### plot()
The function that actually make a plot.
Usually we pass it a set of x values, a set of y values, and the line style and colour we want them plotted using.

#### show()
This actually shows the plots.

#### hold()
We pass this function a True value to make sure that we can plot multiple plots on one set of axes.

#### xlabel()
Sets the x-axis label.

#### ylabel()
Set the y-axis label.

#### legend()
Turns on the legend.
We need to pass the label parameter to plot() for this to work.

## Exercises

1. Change sinewave.py to plot each of the four y value lists using separate plot() funciton calls.

2. Add a grid, and a legend to sinewave.py.

3. Write a script that plots cos(x) and sin(x) on one set of axes but in different colours. Add a legend and a grid. Do this for x values in the range [-4pi,4pi].