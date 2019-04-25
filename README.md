# SPARQL Query Results Visualizer (VizResu)

VizResu, a Web-based service for the visualization and exploration of Linked data retrieved by a public SPARQL endpoint. We use a scholarly data knowledge graph,i.e., EVENTSKG, as a case study in this work. It is intended to support semantic data analysis by visualizing the results of predefined query templates using a web interface.

VizResu Usage Scenario Steps
1.	Select user queries
2.	Select Query parameters
3.	Generate query
4.	Select chart options
5.	Construct chart

In this web service, CORS allows plugin is required for sending and receiving HTTP request and response. This is to bypass the cross-site domain issue. The code base should be enhanced to make it work without that additional plugin.

## Pre-requisite 
Note: For rendering charts, browser need CORS plugin. Install the CORS plugin and run the browser.
https://chrome.google.com/webstore/detail/allow-control-allow-origi/nlfbmbojpeacfghkpbjhddihlkkiljbi?hl=en - Google Chrome

https://addons.mozilla.org/en-US/firefox/addon/cors-plugin/ - Mozila Firefox

