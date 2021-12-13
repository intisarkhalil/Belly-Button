# Belly-Button
## Project Overview:
The purpose of the this project is to to visualize the bacterial data for each volunteer. Specifically,the volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, the volunteers will be able to identify whether that species is found in their navel.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

## Methods:
1.	Use the D3 library to read in samples.json.
2.	Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
    •	Use sample_values as the values for the bar chart.
    •	Use otu_ids as the labels for the bar chart.
    •	Use otu_labels as the hovertext for the chart.
3.	Create a bubble chart that displays each sample.
    •	Use otu_ids for the x values.
    •	Use sample_values for the y values.
    •	Use sample_values for the marker size.
    •	Use otu_ids for the marker colors.
    •	Use otu_labels for the text values.
4.	Display the sample metadata, i.e., an individual's demographic information.
5.	Display each key-value pair from the metadata JSON object somewhere on the page
6.	Update all of the plots any time that a new sample is selected.
Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:
## challenges
The following task is advanced and therefore optional.
    •	Adapt the Gauge Chart from plotly charts documentation to plot the weekly washing frequency of the individual.
    •	You will need to modify the example gauge code to account for values ranging from 0 through 9.
    •	Update the chart whenever a new sample is selected.
## Deployment
Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo.

    •	Use console.log inside of your JavaScript code to see what your data looks like at each step.
    •	Refer to the Plotly.js documentation when building the plots.

