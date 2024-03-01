# Shark Incident Analysis

## Overview
This project aims to analyze shark incident data globally. It utilizes data manipulation and visualization techniques to explore patterns and trends in shark incidents across different countries, continents, and activities.

## Dependencies
* Python 3.x
* Pandas
* NumPy
* Plotly
* Pycountry-Convert

## Data Source
The analysis is based on the GSAF5_file.csv available on GitHub repository, which should be placed in your preferable directory.

## Main Focus
The analyze is mainly focused on the individual activities when the attacks happened.

## Features
* Data cleaning and normalization including handling of country names and converting activity descriptions into categorized groups.

* Visualization of global shark incidents by country using a choropleth map.

* Analysis of incidents over time, categorized by outcome (yes/no).

* Statistical summaries of incidents by activity group, year, country, and continent.

* Custom functions for data transformation and analysis, such as converting country names to continents, categorizing activities, and calculating adjusted risk scores.

## Usage
* Ensure all dependencies are installed using pip install pandas numpy plotly pycountry-convert.
  
* Place the dataset in the specified directory.
  
* Run the script to perform analysis and generate visualizations.
  

## Functions Overview
* Data Cleaning: Functions to lowercase column names, convert floats to ints, and remove spaces.

* Analysis: Functions to categorize activities, convert country names to continents, and filter data based on various criteria.

* Visualization: Utilizing Plotly to create interactive charts and maps for insights into shark incidents.

## Visualizations
* Global map of shark incidents by country.
* Bar charts showing monthly incidents over time.
* Analysis of incidents by activity group, including fishing, water sports, swimming, and surfing.

## Limitations
* The analysis might be limited by the completeness and accuracy of the data in GSAF5_file.csv.
  
* Lack of consistent data can lead to incorrect understand.

## Result
**The analyze demonstrate that surfing even the activity that have more attacks is one of the slowest fatal rates. It also show that swimming even with lower number of attacks is the one most deadly.**

## Presentation
The presentation Ocean Research.pdf is available for further information.

## Credits 
* Feven
* Jedson
* Sergio
* Vinicius

## Original Source
https://www.sharkattackfile.net/

## Future Work
Future iterations could explore more detailed statistical analysis, prediction models for shark incidents, and a broader range of visualization techniques.
