# Data Journalism and D3

![Newsroom](https://media.giphy.com/media/v2xIous7mnEYg/giphy.gif)

## Scenario

Welcome to the newsroom! You've just accepted a data visualization position for a major metro paper. You're tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs, and interactive elements to help readers understand your findings.

The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.

The data set included with the assignment is based on 2014 ACS 1-year estimates from the [US Census Bureau](https://data.census.gov/cedsci/), but you are free to investigate a different data set. The current data set includes data on rates of income, obesity, poverty, etc. by state. MOE stands for "margin of error."


### D3 Dabbler 

![Graph](Images/graph-1.jpg)

Create a scatter plot between two of the data variables such as `Smokers vs. Age`.

Using the D3 techniques, I created a scatter plot that represents each state with circle elements. I coded this graphic in the `app.js` file via the data from `data.csv`, using the `d3.csv` function. Lastly, I created and situated my axes and labels to the left and bottom of the chart. My plot included the state abbreviations in the circles.
   

* Note: You'll need to use `python -m http.server` to run the visualization. This will host the page at `localhost:8000` in your web browser.

## Alicia Ly
