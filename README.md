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

I am generally interested in health data over countries especially in the different causes of deaths. While I was looking for [this chart](https://www.perceptualedge.com/example20.php) I came across a chart that talked about the deaths due to air pollution and it got me intrigued. Check the viusalization below: (https://ourworldindata.org/grapher/death-rates-from-air-pollution)

![Deaths due to Air Pollution](https://github.com/ketakisrao/KetakiRao-TSWD-Portfolio/blob/master/AirPollution.png)

