# D3
## Link: https://cherngywh.github.io/D3/

**Background**

*Welcome to the newsroom! You've just accepted a data visualization position for a major metro paper. You're tasked with analyzing the current trends shaping people's lives, as well as creating charts, graphs and interactives to help readers understand your findings.*

*The editor wants to run a series of feature stories about the health risks facing particular demographics. She's counting on you to sniff out the first story idea by sifting through the latest information from the U.S. Census Bureau and the Behavioral Risk Factor Surveillance System.*

*The beat reporters will go out and investigate the relationship you find, sourcing experts and finding anecdotes to back up your research. That's tough work, and they won't be happy about digging for a story that doesn't exist—you'll need to find a convincing correlation before you even think about pitching your first article. The editor also wants you to make a scatter plot to show the correlation—you are the data visualizer, after all.*

**Step 1: Find the Data**

*- Specify the information using the  [American FactFinder](https://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml) tool*<br/>
*- Search for data on health risks using 2014 survey data from the [Behavioral Risk Factor Surveillance System](https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-2014-Overall/5ra3-ixqq), filter the Question data on the site before downloading a specified .csv.*<br/>
*- Let's format the data for D3.*<br/>
*- To make sure we have a solid trend,  test for correlation with Excel's =CORREL() function.*<br/>
*- Save the file as data.csv and place it in the data folder.*

**Step 2: Visualize the Data**

*- Using the D3 techniques to create a scatter plot that represents each state with circle elements. Generate the chart in the d3.html displays the graphic just as we'd like it to, embed it in index.html with an iframe.*<br/>
*- Include state abbreviations in the circles and create and situate the axes and labels to the left and bottom of the chart.*<br/>
*- Include three demographics and three risks. Place additional labels in the scatter plot and give them click events so that users can decide which data to display. Animate the transitions for the circles' locations as well as the range of your axes.*<br/>
*- Add tooltips to the circles and display each tooltip with the data that the user has selected. Use the d3-tip.js plugin developed by [Justin Palmer](https://github.com/Caged).*<br/>
*- Add responsive function to optimize the scatter plot so that its data is accessible to all users.*
