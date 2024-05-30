## Overview
This project aims to analyze road accident data extracted from Kaggle using Tableau. The dataset, originally named `Road Accident Data.csv`, was sourced from [Kaggle](https://www.kaggle.com/datasets/nextmillionaire/car-accident-dataset). It contains detailed information about road accidents, including factors such as accident date, time, weather conditions, road surface conditions, light conditions, and more.

## Dataset
The dataset `Road Accident Data.csv` consists of records of road accidents, each containing information such as the accident date, day of the week, junction control, accident severity, latitude, longitude, number of casualties, number of vehicles involved, police force, road surface conditions, speed limit, urban or rural area, weather conditions, and vehicle type.

## Cleaning Process
The dataset underwent a cleaning process to ensure data integrity and consistency. Using Python's pandas library, common data cleaning tasks were performed, including converting date and time columns to datetime format, standardizing column names and text values to lowercase, and saving the cleaned dataset as `Cleaned_Road_Accident_Data.csv`.

## Visualization
The cleaned dataset was uploaded to Tableau for visualization and analysis. Visualizations, dashboards, and stories were created to explore various aspects of the data, such as identifying accident hotspots, analyzing factors contributing to accidents, and examining trends over time.

## How to Use
1. **Accessing the Dataset**: The cleaned dataset `Cleaned_Road_Accident_Data.csv` can be found in the repository.
2. **Data Cleaning**: If you wish to replicate the data cleaning process, refer to the Python script, named as `TASK05.ipynb`, provided in the repository.
3. **Visualization**: The Tableau visualizations of the road accident data are available in the Tableau workbook, named as `AccidentAnalysis.twbx`, provided in the repository.

## Note
Due to file size limitations, we couldn't upload the original and cleaned datasets (`Road Accident Data.csv` and `Cleaned_Road_Accident_Data.csv`) directly to this repository as they exceeded 25MB. However, the Tableau visualizations and Python script used for data cleaning are provided for reference.
