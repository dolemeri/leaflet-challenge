#  UofT - Data Analysis Boot Camp

### Module 15 Mapping

### belly-button-challenge

### Background

An interactive dashboard was built with javascript to explore the Belly Button Biodiversity, which catalogs the microbes that colonize human navels.

## Tools

- Javascript
- D3
- HTML
- Plotly

## Key Steps

#### **JSON Data**

Used D3 to read in sample JSON data from a sample [url](https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json).

````
function init() {
    //Import json data
    d3.json(url).then((jsonDatadata) => {
        data = jsonDatadata; // Store the JSON data as a variable
        console.log(data); 
  
````
