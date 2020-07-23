# Storytelling With Data

Welcome to my online portfolio for the Storytelling with Data class.

# About Me

I am a student from the Master of Human Computer Interaction program at School of Computer Science, Carnegie Mellon. I enjoy working working with data sets and like to build viusalisations on them to be able to showcase what the data is about and what one needs to know from it. I've worked on a very diverse range of datasets, from MSF(Doctors without Borders) data to a dataset that I made based on Cheeses. One of my favourite viusalisation is [Napoleon’s invasion of Russia](https://miro.medium.com/max/4006/1*V9sq--wHI1wm1zA3Gng1sg.png). Here is a link to my favourite [charting library](https://www.amcharts.com/).

Some of my previous works are:
* [Met Museum](https://ketakisrao.github.io/Met/)
* [Say Cheese](https://ketakisrao.github.io/CMUPortfolio/saycheese.html)

# What I hope to learn?

I want to be able to learn how to creatively & effectively show data that looks boring in tables and is also not very readable/comparable. I want to know the role of color, size, typography, etc in making a visualization effective or ineffective(on thing that I've learned being in a design program is that knowing what not to is as important as knowing what to do). I want to understand how testing can play a role in improving data visualizations and how I can extend my HCI knowledge to make  visualisations compelling and easy to understand.

# Portfolio

This is where I will post my interesting journey through the Telling Stories with Data class.


## Analysing Government Debt



Government debt, also known as national debt, can be described as the difference between a country’s receipts and their spending. It is generally expressed as a percentage of GDP. Below is a simple bar chart of the Government debts in 2019. Below is the latest data for government debt of these selected countries. This bar chart helps you compare and contrast the debt to GDP ratio of these countries.


<iframe src="https://data.oecd.org/chart/61Rx" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/61Rx" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2019</a></iframe>

<br><br>
### Visualising trends in Government Debt to GDP ratio over the years 1995 - 2019
The same government debt to GDP ratios have been plotted below. This time, I have made use of this sparklines grid chart. This chart enables us to see the trends in the government debt to GDP ratio per country over time (1995-2019). Plotting the data this way reveals some interesting insights about it. For example:

1. It is evident that the debt to GDP ratio for **Ireland** peaked during the years of 2012 and 2013.
2. **Denmark** saw its lowest debt to GDP ratio in the year 2007
3. The debt to GDP ratio for **Japan** has always been trending upwards, i.e. debt kept rising year after year.


<iframe src='https://flo.uri.sh/visualisation/3148220/embed' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3148220/?utm_source=embed&utm_campaign=visualisation/3148220' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>


### Mapping the absolute values of debt per country with their GDP and population
<br><br>
For this third type of visualization, I wanted to be able to see how I can visualize the real debt of these countries. I also wanted to be able to see whether the population of a country affects the debt it is in. So I’ve merged this dataset with a dataset with the country’s corresponding population & GDP and plotted this scatter plot or a bubble chart (as many of you call it). I’ve assigned the (absolute)amount of debt each country has to the size of the corresponding bubble.

This makes it easy to see that population as the population of a country increases, so does the debt, since the bigger circles are higher up on the x axis. (It is also almost obvious that country with a higher GDP will have a bigger value of absolute debt)


<iframe src='https://flo.uri.sh/visualisation/3149327/embed' frameborder='0' scrolling='no' style='width:100%;height:600px;'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/3149327/?utm_source=embed&utm_campaign=visualisation/3149327' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>




## Redesign of a chart and testing with user feedback

### Air Pollution

I am generally interested in health data over countries especially in the different causes of deaths. While I was looking for [this chart](https://www.perceptualedge.com/example20.php) I came across a chart that talked about the trend in deaths due to air pollution and it got me intrigued. Check the viusalization below: (https://ourworldindata.org/grapher/death-rates-from-air-pollution)

![Trends in Deaths due to Air Pollution](https://raw.githubusercontent.com/ketakisrao/KetakiRao-TSWD-Portfolio/master/AirPollution.png)

This particular chart is a part of a bigger story that talks about the deaths due to air pollution and the whole intent of this chart is to show that even though the total deaths due to air pollution are decreasing the actual reason behind it is better indoor conditions and not outdoor pollution, ie improved indoor air conditions are the contributors to reduction in deaths due to air pollution. Here is my critique of the above chart:

**Pros:**
1. The trend is captured by the line chart.
2. The correct source of data has been attributed.

**Cons:**
1. The main message of this chart is to show that deaths due to air pollution have significantly decreased due to improved indoor air conditions. But this seems to get lost with all the color in the chart.
2. The background/grid lines are of the same thickness as the chart lines which adds to the confusion.
3. There needs to be some kind of emphasis on the indoor pollution line for it to grab the viewer's attention immediately.
4. More data points in the number of years makes it harder to notice that outdoor pollution and outdoor ozone pollution have remained almost constant throughout.
5. The chart’s title needs to be more engaging and descriptive about what the viewer should expect in the chart before reading the explanation.


So I decided to work on improving this chart by simplifying it into a slope chart with lesser colors and making design changes so as to call attention to the parts which get the message across. Here is my first iteration:
![Redesign of Deaths due to Air Pollution](https://raw.githubusercontent.com/ketakisrao/KetakiRao-TSWD-Portfolio/master/RedesignAirPollution.jpg)

#### Design Decisions
1. Made the title more engaging and descriptive so that users know what to expect in the chart.
2. Made the lines for indoor air pollution and total air pollution thicker so as to call attention to them.
3. Got rid of the grid lines as they add to the "visual clutter" in the chart.
4. Changed the chart type to slope charts so that the trends are easily visible.
5. Grayed out the "other" (not so important pieces) of the chart.


### Feedback received on testing the redesigned chart (Person 1)
1. Impact of air pollution on health/fatality.
2. This is telling the total number of people died due to air pollution has actually decreased.
3. Surprising/confusing because outdoor air pollution has no impact on fatality.
4. Organizations/govts anyone  who contribute to air pollution.
5. I would have more datapoints.


### Feedback received on testing the redesigned chart (Person 2)
1. The title is short but confusing.
2. Not having labels on X and Y axes makes it confusing to understand the data it represents. I thought having the scale in 1000s would make it clear that the y axis refers to number of deaths but the viewers mistook it for the total amount of air pollution.
3. But the message from the chart is pretty clear and is pretty intuitive.


### Final version of the chart

![Final Redesigned Chart](https://raw.githubusercontent.com/ketakisrao/KetakiRao-TSWD-Portfolio/master/Final%20Redesign.png)

This is the final redesign of the Air Pollution chart. Changes made:
1. Changed the title to be more descriptive.
2. Added labels to y axis and appended "year" to x axis items in order to make the chart data easier to interpret. (removing ambiguity)
3. Added source for credibility.


<iframe seamless frameborder="0" src="https://public.tableau.com/profile/ketakisrao#!/vizhome/AirPollutionDeathChart/Sheet1?publish=yes" width = '650' height = '450'></iframe>

<div class='tableauPlaceholder' id='viz1595546220283' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ai&#47;AirPollutionChartremake&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='AirPollutionChartremake&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ai&#47;AirPollutionChartremake&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /><param name='filter' value='publish=yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1595546220283');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
