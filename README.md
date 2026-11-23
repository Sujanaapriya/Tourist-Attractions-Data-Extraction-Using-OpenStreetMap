# Tourist Attractions Data Extraction and Analysis Using OpenStreetMap

## 1. Project Overview

This project focuses on extracting, cleaning, and analysing tourist attraction data from OpenStreetMap (OSM) for Mysuru, Karnataka, India.

The project uses the Overpass API to retrieve information about tourist attractions such as monuments, museums, parks, and historical places. The extracted data is processed and organised into a structured dataset for further analysis.

## 2. Problem Statement

Tourist attraction information is available across different online sources, but it may not always be organised in a structured format.

This project aims to collect publicly available geographical information about tourist attractions in Mysuru using OpenStreetMap and transform it into a clean, structured dataset.

## 3. Objectives

- Extract tourist attraction data using the OpenStreetMap Overpass API.
- Identify different types of tourist attractions in Mysuru.
- Extract geographical details such as latitude and longitude.
- Clean and organise the extracted data.
- Perform basic exploratory data analysis.
- Save the final dataset in CSV format.

## 4. Tools and Technologies

- Python
- Google Colab
- Overpass API
- OpenStreetMap
- Pandas
- Matplotlib
- Seaborn

## 5. Data Source

**OpenStreetMap (OSM)**

OpenStreetMap is a collaborative, open geographical database that provides information about locations and geographical features.

- Website: https://www.openstreetmap.org/
- Overpass API: https://overpass-api.de/

The project uses the Overpass API to retrieve tourist attraction information based on relevant OpenStreetMap tags.

## 6. Dataset Description

The final dataset is organised with the following fields:

| Column           | Description |
|---|---|
| Attraction Name  | Name of the tourist attraction |
| Attraction Type  | Category or type of attraction |
| Latitude         | Geographical latitude |
| Longitude        | Geographical longitude |
| City/Location    | Location associated with the attraction |
`mysuru_tourist_attractions.csv`

## 7. Methodology

The project follows these steps:

1. **Location Identification:** Identify the Mysuru geographical area using location data.
2. **Data Extraction:** Retrieve tourist attraction records through the Overpass API.
3. **Data Processing:** Convert the API response into a structured tabular format.
4. **Data Cleaning:** Handle missing values, remove duplicate records, and validate geographical coordinates.
5. **Exploratory Data Analysis:** Examine the dataset, check missing values, and analyse attraction-type distribution.
6. **Data Export:** Save the cleaned dataset as a CSV file.

## 8. Exploratory Data Analysis

The project includes:

- Preview of the extracted dataset.
- Missing-value analysis.
- Distribution of tourist attractions by type.
- Summary metrics of the final dataset.


## 9. Limitations

- The completeness of the dataset depends on the information available in OpenStreetMap.
- Some tourist attractions may not have names or complete geographical details.
- The results depend on the relevant OpenStreetMap tags and the geographical boundary used.
- API availability and response times may affect data extraction.

## 10. Future Enhancements

- Extend the analysis to other cities and districts.
- Perform geographical visualisation of tourist attractions on an interactive map.
- Analyse attraction density across different areas.
- Integrate additional tourism-related datasets.

## 11. Acknowledgement

This project uses geographical data from OpenStreetMap contributors.

© OpenStreetMap contributors  
https://www.openstreetmap.org/copyright
