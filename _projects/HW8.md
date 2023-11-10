---
name: Buildings Data Visualization
tools: [Python, HTML, Altair]
image: assets/pngs/interactive_legend.png
description: For HW8! Data visualizations for the buildings dataset.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


### Plot 1:

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_bar.json" style="width: 100%"></vegachart>

### Write-Up for Plot 1

This scatter plot is showing the year constructed vs the number of floors for the buildings based on what the building is being used for. For interactivity, the user is able to choose the use of the building to see the scatter plot for various uses. I chose to base the color on the total floors to make it more visually appealing. The square footage is also displayed when hovering over a data point. With the dropdown and the square footfage being presented when hovering, there is interactivity. 

### Plot 2:

<vegachart schema-url="{{ site.baseurl }}/assets/json/final_line.json" style="width: 100%"></vegachart>

### Write-Up for Plot 2

This line graph is showing the total floors vs the mean square footage for the buildings. I decided to use the mean square footage because I thought this was more relevant. Everything is quantitative since it is all straight numbers. I did not not use a color scheme since it is just one line. Overall, this is a relatively simple graph with no interactivity.


<div class="left">
{% include elements/button.html link="https://github.com/dmgaron2/dmgaron2.github.io/blob/master/_projects/HW8.md" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/dmgaron2/dmgaron2.github.io/blob/master/python_notebooks/HW8.ipynb" text="The Analysis" %}
</div>

