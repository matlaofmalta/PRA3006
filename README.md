# PRA3006 Group 2

## User Instructions
Open this HTML file in your preferred browser ""

If this does not work:
1. Open a new VS code window, click "**Clone Git Repository**".
2. Insert https://github.com/matlaofmalta/PRA3006.git into your VS code search bar.
3. Right-click the "**index.html**" file and select "**Reveal in File Explorer**" to see the webpage.


## About the Project

**Research Question**: *What are the relationships between Dementia and its associated symptoms and treatments, and how does the prevalence of this disease vary globally?*

This project aims to create an interactive platform where web users can learn about dementia, its treatments and global relevance. 

Our webpage homepage starts by defining dementia and listing the different types that exist. It also delves into the signs and symptoms of dementia presented in an interactive manner and potential dementia risk factors. The programming languages used for the webpage homepage include HTML and CSS for the web page layout and design. 

Our **“Learn about Current treatments”** tab presents a network graph of the types of drugs used to treat dementia and their functions. You can click on each data point of this graph to get further information on the drug and its specific function(s). The data to make this graph is extracted from Wikidata using a SPARQL query. The network graph was created using the javascript library d3.js and CSS to create an interactive clicking element at the nodes and to design the graph. 

The **“Prevalence of Dementia”** page interactively shows regional estimates of dementia from 2015 to 2035. This geospatial visualization is a Bubble map, where the prevalence is portrayed according to bubble size, and the most affected regions have darker colours. The data for this visualisation is extracted from Wikidata using a SPARQL query. You can click on each region affected for further information on the number of (predicted) dementia cases. 

The interactive map was created using the CSS sheet Leaflet which creates interactive maps. The javascript library JQuery was used for shorter syntax than javascript and because it can handle browser inconsistencies. 

Lastly, the “Relevant Sources” tab provides more informative links for curious web page users who want to learn more about dementia. The authors' contact information will also be available on this tab.

