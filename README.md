# VISUALISING ROAD ACCIDENTS IN THE UK
## Steps to Get Started (You can skip to the visualisation stage without going through the others)
### Data Preparation with Tableau Prep
1. Open the file "data_prep.tfl" to get the flow used in preparing the data.
2. Make sure your input is directed to "/UK_Accident.csv".
3. Set the location path for your output file.
4. Run the flow.

### Data Understanding
1. Open the file "description.py" in any text editor or IDE of your choice.
2. On line 45, replace 'data.csv' with the path to your output file from the Data Preparation stage.
3. On line 46, replace 'output.txt' with the file path and name you would like to use for your output file.

### Data Visualisation
1. Open "Dissertation.twb" with Tableau Desktop.
2. Make sure your data sources are connected to the right files: "Dissertation" being the csv file output from the Data Preparation stage(Dissertation_data.csv if you did not follow the above stages) and "Dissertation_Spatial_Data.geojson" being the spatial file.
3. Connect using "Extract" or "Live" data and enjoy the visualisations.
