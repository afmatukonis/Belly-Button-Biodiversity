# Belly-Button-Biodiversity
Module-13


Link: https://afmatukonis.github.io/Belly-Button-Biodiversity/


**Overview**

The purpose of this module is to create a dashboard using Plotly, JavaScript, and HTML using a JSON file of bacterial data found in volunteers belly buttons. We were tasked with creating a horizontal bar chart, bubble chart, gauge chart, and customizing the dashboard with text, colors, and pictures. 

First before we created any charts we had to build the HTML page and import the json file and build charts. We created a demographic panel using this code: 

function buildMetadata(sample) {
  d3.json("samples.json").then((data) => {
   });
   }

We then had to create the build chart and use d3.json to load the samples.json file in. 

![Screen Shot 2023-02-28 at 12 09 00 AM](https://user-images.githubusercontent.com/118235205/221792192-e4b4cdc9-d95c-4126-a357-f64a84f57a05.png)


**Deliverable 1**

The first deliverable was to create a horizontal bar chart using JavaScript, Plotly, and D3,js to display the top 10 bacterial species (OTUs) when an individual was selected from a dropdown. 

**Deliverable 2**

The second deliverable was to create a bubble chart that will display the otu_ids as the x-axis, the sample_values as the y-axis, the sample_values as the marker size, the otu_ids as the marker colors, and the otu_laables as hover-text values.

**Deliveable 3**

The third deliverable was to create a gauge chart that displayed the weekly washing frequency value measured from 0-10 on a progress scale. Like the other two charts this was dependent on the id drop down menu. 

**Analysis**

Based on the dashboard created we can see the top 10 bacterial OTUs for each volunteer as well as the bacterial cultures per sample and the washing frequency and interact with the data. To make my website stand out I added a graphic image in the header and adjusted the color wheel for the gauge chart to make it more appealing, as well as increased text size and changed the font.


