# Location Suitability Analysis For Space Situational Awareness (SSA) Observations

A small study on the optimal location for SSA Sensors



The Project Started with running several scripts located within main. 

Dark Times, Night Light and Satellties Traces were calcualted in these Jupyter Notebooks.

Data was collected from NASA Earth Obervations (Water Vapour, Cloud Fraction), VIIRS DNB from Earth Observation Group and the GLOBE DEM was utilized. 

All of these crteria were combined in ArcGIS Pro with a Model to Normalize and combine the data in monthly composites. 

Starlink launch cadences were found and a weight based on montht of launch was created. These weight were mutlipled by the monthyl composites to create a yearly composite map that shows the ideal location of an SSA sensor.
