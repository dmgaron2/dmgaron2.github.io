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

This scatter plot is showing the year constructed vs the number of floors for the buildings based on what the building is being used for. 

### Plot 2:

<vegachart schema-url="{{ site.baseurl }}/assets/json/chart2.json" style="width: 100%"></vegachart>

### Write_Up for Plot 2

This bar chart is showing 

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

