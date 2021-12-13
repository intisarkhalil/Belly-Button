# Belly-Button
## Project Overview:
The purpose of the this project is to to visualize the bacterial data for each volunteer. Specifically,the volunteers should be able to identify the top 10 bacterial species in their belly buttons. That way, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, the volunteers will be able to identify whether that species is found in their navel.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
## Methodology:
1.	Use the D3 library to read in samples.json.
2.	Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
```
•	Use sample_values as the values for the bar chart.
•	Use otu_ids as the labels for the bar chart.
•	Use otu_labels as the hovertext for the chart.
```  
3.	Create a bubble chart that displays each sample.
```
•	Use otu_ids for the x values.
•	Use sample_values for the y values.
•	Use sample_values for the marker size.
•	Use otu_ids for the marker colors.
•	Use otu_labels for the text values.
 ```   
4. Create a Gauge Chart.
```
- Creates a title for the chart.
- Creates the ranges for the gauge in increments of two, with a different color for each increment.
- Adds the washing frequency value on the gauge chart.
- The indicator shows the level for the washing frequency on the gauge.
- The gauge is added to the dashboard.
- The gauge fits in the margin of the <div> element.
``` 
6.	Display the sample metadata, i.e., an individual's demographic information.
7.	Display each key-value pair from the metadata JSON object somewhere on the page
8.	Update all of the plots any time that a new sample is selected.
Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown below:
## Customize the Dashboard.
1. The webpage has three customizations. 
```
- Add an image to the jumbotron.
- Add information about what each graph visualizes, either under or next to each graph.
- Make the webpage mobile-responsive.
```
3. When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu.
## Results.
https://intisarkhalil.github.io/Belly-Button/

![ggggg](https://user-images.githubusercontent.com/62036983/145744164-6c59f09b-f359-4d78-932e-475a3ba89409.png)

    
    
