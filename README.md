# Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Background

This task mainly comprises of analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand the findings. It's achieved by sifting through the latest information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

### Task 1: D3 Dabbler

![4-scatter](Images/4-scatter.jpg)

To obtain the image above, D3 techniques are used to create a scatter plot between two of the data variables such as `Healthcare vs. Poverty` or `Smokers vs. Age` that represents each state with circle elements. This graphic is coded in the `app.js` file of the directory and data is pulled in from `data.csv` by using the `d3.csv` function.

In addition to this, `python -m http-server` is used to run the visualization. This will host the page at `localhost:8000` in the web browser.
- - -

### Task 2: Interacting with our data

![7-animated-scatter](Images/7-animated-scatter.gif)

#### 1. More Data, More Dynamics

To interact with our data, more demographics and risk factors are included. To obtain this, additional labels are placed in the scatter plot and given click events so that users can decide which data to display. Then, the transitions for circles' locations as well as the range of the axes animated. This is done for three risk factors for each axis.

#### 2. Incorporate d3-tip

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Tooltips are added to circles and each tooltip is displayed  with the data that the user has selected. The `d3-tip.js` plugin used is developed by [Justin Palmer](https://github.com/Caged).

![8-tooltip](Images/8-tooltip.gif)
- - -
