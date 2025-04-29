# MSE110_Final_Project

MSE110 Final Project Code Descriptions

Prompt 1.1
Description: Create a simple script that retrieves and compares the band gaps of metal oxides versus metal nitrides (e.g., TiO2 vs TiN). Generate a basic bar chart showing these differences for 5-10 different metals.
What my Code Does: This code compares how well different metals conduct electricity when combined with oxygen or nitrogen. It uses the Materials Project API key to connect to a materials database to get band gap data for compounds like metal oxides and nitrides. It then it creates a bar chart to show the differences in band gaps for each metal.


Prompt 5.1
Description: Create a tool that identifies materials with band gaps in the ideal range for solar cells (1.1-1.7 eV) and ranks them by stability (energy above hull).
What my Code Does: This code uses the Materials Project API key and database to identify materials with band gaps between 1.1 and 1.7 eV and low energy. It retrieves material data such as ID, formula, band gap, and energy above hull and organizes it in a DataFrame. It then uses Plotly to organize the information into a scatterplot.


