# London-air-quality

This project is for portfolio and demonstration purposes only. Reuse or redistribution of the code is not permitted.

## Data sources

The primary data source was the London Atmospheric Emissions Inventory 2022 (link [here](https://data.london.gov.uk/dataset/london-atmospheric-emissions-inventory-laei-2022-2lg5g/)), which is available to the public via the London Datastore.

The LAEI2019_grid shapefile was taken from the  within the "Supporting Information - GIS Geographies" zip folder ->
"LAEI2022-Supporting-Information-GIS-Files" folder -> "Shapefile SHP" folder. More specifically: the following files were taken:

* LAEI2019_grid.cpg
* LAEI2019_grid.dbf
* LAEI2019_grid.prj
* LAEI2019_grid.shp
* LAEI2019_grid.shx

The particulate matter (PM) 2.5 annual average concentrations data was taken from the "Concentrations - Data - CSV files" zip folder -> "CSV" folder. More specifically: the "LAEI2022_V1_PM25.csv" file was taken.

## Technical notes

This analysis was conducted on a personal laptop with 4 GB of installed RAM and an Intel(R) N150 800 MHz processor. The laptop's specification was intended for everyday web browsing and low-intensity office tasks (e.g. word processing, spreadsheets), not for processing high-resolution geospatial data for the whole of London. Anyone wishing to expand this analysis to cover the whole of London is advised to use hardware designed for processing large volumes of data (e.g. a high-specification laptop, a virtual machine) to maximise speed of code execution.

## Credits

Extensive online search was required to a) construct the Python code (e.g. referring to Folium and GeoPandas documentation) and b) integrate the Jupyter notebook with Quarto and GitHub Pages for online presentation. Special mention goes to **Python Graph Gallery** (link [here](python-graph-gallery.com)) and **Stack Overflow.**

## Use of generative AI

Google Gemini and Microsoft Copilot were used to answer technical queries (e.g. about Python coding syntax, geospatial data visualisation) as well as queries relating to air quality and London. Accuracy of responses was confirmed by viewing the source web pages and adjacent online search results.
