# BDE_Project

<h2>Awards</h2>
<img src="https://i.imgur.com/IrEiIDi.jpg" />

### Description

## Dashboard
An interactive data analysis & visualizations dashboard using python libraries including streamlit, pandas, matplotlib, plotly, pydeck, etc. for the Baker Hughes Gas Turbine dataset. The dashboard is deployed on Streamlit and can be accessed ![here](https://jay4codes-tamu-datathon-main-orrlds.streamlit.app/)

## Data Pipeline
We have multiple engine data and site data
Each site has multiple engines

Two lookup files
- engine_metadata
- site_metadata

In data directory at end of each day a csv is added that has logs of the engine data for all each plant
This data undegoes the following analysis
- Filling null values
- Renaming column ID
- Dropping redundant columns
- Calculating Thermal effiency
- Creates a new dataframe with new columns

Google Cloud Platform metadata
Region - US
Zone - us-central
