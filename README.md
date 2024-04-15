# NYC Taxi Data Analysis

## Project Overview

This project analyzes extensive data from New York City taxi trips to uncover insights into taxi utilization and inter-borough mobility. 
Utilizing Spark and Python, the analysis delves into several key aspects of urban transportation, such as trip durations, wait times between fares, and the geographical flow of taxis across different boroughs. 
The project aims to enhance understanding of taxi service dynamics, which can inform better resource allocation and operational strategies for taxi services in urban settings.

### Key Queries Addressed

1. Utilization Rates: Calculate the utilization rates of taxis, focusing on the active vs idle time of each taxi to assess efficiency.
2. Time to Next Fare: Analyze the average time taxis spend waiting for the next fare in each borough, highlighting areas with the highest and lowest efficiencies.
3. Intra-borough Trips: Count the number of trips that start and end within the same borough, giving insights into local mobility.
4. Inter-borough Trips: Quantify the trips that start in one borough and end in another, providing data on broader urban travel patterns.


### Data Sources

`sample.csv`: Contains detailed records of individual taxi trips, including timestamps and geographical coordinates for pickups and drop-offs.

`nyc-boroughs.geojson`: Geospatial data defining the boundaries of NYC boroughs, used to enrich the taxi trip data with borough information.


### Technologies Used

- Python: Primary programming language for data processing and analysis.
- Pandas and GeoPandas: Libraries used for data manipulation and geospatial analysis.
- Apache Spark: Utilized for handling large-scale data processing efficiently.
- Shapely: Library for geometric operations, used to determine the relation of geographical points to borough boundaries.

## Setup and Running the Project

### Prerequisites
Ensure you have Python installed, along with Pandas, GeoPandas, Shapely, and PySpark. You can install these with pip:
```
pip install pandas geopandas shapely pyspark
```

### Data Setup
Place your `sample.csv` and `nyc-boroughs.geojson` in a directory accessible by the scripts.

### How to Run:
Clone this repository to your local machine.
Navigate to the directory containing the project files.
Run the Python scripts or Jupyter notebooks (if applicable) to perform the analysis:
```
python Project1.py
```

## Results and Discussion

This section can be used to discuss the findings from each of the key queries. Visualizations and insights derived from the analysis should be included to illustrate how taxi services operate across different parts of the city and at different times.

## Conclusion

Summarize the implications of the findings for city planners, taxi companies, and other stakeholders interested in improving urban mobility and taxi service efficiency.
