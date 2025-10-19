# headline_disease_geotracker
Tracking disease outbreaks using news headlines

Problem statement:
 process the daily quota of news
 headlines and extract locations that are mentioned You will then cluster the
 headlines based on their geographic distribution. Finally, you will review the
 largest clusters within and outside the United States. Any interesting findings
 should be reported to your immediate superior.
 
Our goal is to extract locations from disease-related headlines to uncover the larg
est active epidemics within and outside of the United States. We will do as follows:
 1 Load the data.
 2 Extract locations from the text using regular expressions and the GeoNamesCache library.
 3 Check the location matches for errors.
 4 Cluster the locations based on geographic distance.
 5 Visualize the clusters on a map, and remove any errors.
 6 Output representative locations from the largest clusters to draw interesting conclusions.
