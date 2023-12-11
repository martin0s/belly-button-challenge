# belly-button-challenge

# Instructions
Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use sample_values as the values for the bar chart.

* Use otu_ids as the labels for the bar chart.

* Use otu_labels as the hovertext for the chart.

![image](https://github.com/martin0s/belly-button-challenge/assets/61669834/0222a65f-905a-4a2d-b920-5335cf66d412)

3. Create a bubble chart that displays each sample.

* Use otu_ids for the x values.

* Use sample_values for the y values.

* Use sample_values for the marker size.

* Use otu_ids for the marker colors.

* Use otu_labels for the text values.

![image](https://github.com/martin0s/belly-button-challenge/assets/61669834/4587b0ef-8a20-4648-93d2-d2d20cb48935)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://github.com/martin0s/belly-button-challenge/assets/61669834/041ef563-5675-4c53-b349-0feeaf2d78fc)

6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

![image](https://github.com/martin0s/belly-button-challenge/assets/61669834/80aef65f-cb02-4d79-a41f-9120346979a7)

7. Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits and a thorough README.md file

# Advanced Challenge Assignment (Optional with no extra points earning)
The following task is advanced and therefore optional.

* Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

* You will need to modify the example gauge code to account for values ranging from 0 through 9.

* Update the chart whenever a new sample is selected.

![image](https://github.com/martin0s/belly-button-challenge/assets/61669834/e15cef51-1729-42dd-abc2-1b2e8ebcc5e5)

