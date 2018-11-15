# Belly Button Biodiversity

In this assignment we have to build an interactive dashboard to explore the following: 

## Plotly.js

By using Plotly.js we have to build interactive charts for our dashboard.

* A PIE chart is created that uses data from our samples route (`/samples/<sample>`) to display the top 10 samples.

  * `sample_values` are used as the values for the PIE chart.

  * `otu_ids` is used as the labels for the pie chart.

  * `otu_labels` is used as the hovertext for the chart

  ![PIE Chart](Images/pie_chart.png)

* Bubble Chart 

* Bubble chart is used to display each sample made from the data of our samples route(`/samples/<sample>`).

  * `otu_ids` is used for the x values.

  * `sample_values` is used for the y values.

  * `sample_values` is used for the marker size.

  * `otu_ids` is used for the marker colors.

  * `otu_labels` is used for the text values.

  ![Bubble Chart](Images/bubble_chart.png)

* Display of the sample metadata from the route `/metadata/<sample>`

  * Display of each key/value pair from the metadata JSON object somewhere on the page.

## Step 2 - Heroku

Step 2 involves the deployment of FLASK app to Heroku for which sqlite files is used for the database.