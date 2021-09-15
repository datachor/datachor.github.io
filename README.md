# Plotly_challenge
An interactive dashboard has been created
Data: Belly Button Biodiversity

![Bacteria by filterforge.com](Images/bacteria.jpg)

An interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels was created.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

Step 1 involved using Plotly

1. The D3 library was used to read in `samples.json`.

2. A horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual was creaated.

* `sample_values` were used as the values for the bar chart.

* `otu_ids` were used as the labels for the bar chart.

* `otu_labels` were used as the hovertext for the chart.

[bar Chart](Images/hw01.png)

3. A bubble chart that displays each sample was created.

* `otu_ids` were used for the x values.

* `sample_values` were used for the y values.

* `sample_values` were used for the marker size.

* `otu_ids` were used for the marker colors.

* `otu_labels` were used for the text values.

[Bubble Chart](Images/bubble_chart.png)

4. The sample metadata, i.e., an individual's demographic information were displayed.

5. Each key-value pair from the metadata JSON object were displayed on the page.

(Images/hw03.png)

6. All of the plots are updated any time that a new sample is selected.
