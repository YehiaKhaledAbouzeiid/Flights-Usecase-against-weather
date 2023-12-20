# Flight Analysis with Python

## Overview

This project delves into flight data using Python libraries like pandas, matplotlib, and scipy to explore various aspects of flight performance, delays, and weather impacts.

## Data

- **flights.csv:** Contains information about individual flights, including origin, destination, carrier, arrival/departure times, delays, and more.
- **weather.csv:** Provides weather data for each flight, including temperature, humidity, visibility, precipitation, etc.

## Analysis

1. **Flight Overview:**
   - Explores the dataset, examining its shape, columns, data types, and unique destinations.

2. **Seattle Flights:**
   - Focuses on flights arriving in Seattle, analyzing the number of carriers, unique tail numbers, average arrival delay, and origin distribution.

3. **Delay Analysis:**
   - Identifies days with the highest average departure and arrival delays, and the day with the most overall delayed flights.

4. **Monthly and Hourly Trends:**
   - Investigates the average departure delay trends across months and hours of the day.

5. **Flight Speed:**
   - Calculates the speed of each flight and finds the fastest one.

6. **Reliable Flights:**
   - Discovers flights that operate every day of the year for specific carrier-flight-destination combinations.

7. **Carrier Comparisons:**
   - Compares the average departure and arrival delays for carriers flying to Seattle.

8. **Weather Impact:**
   - Merges weather data with flight information to explore the relationship between various weather factors and departure delays. Visualization scatter plots reveal potential correlations.

## Key Findings

- Seattle receives flights from numerous carriers with unique aircraft.
- Departure delays vary over months and hours, with specific days experiencing higher averages.
- Certain flight combinations operate consistently throughout the year.
- Carrier performance on departure and arrival delays can differ.
- Weather factors like humidity, dew point, and precipitation may influence departure delays.

## Further Explorations

- Analyze factors like weather in the destination city.
- Investigate other delay causes like mechanical issues or air traffic control.
- Develop predictive models for flight delays based on various factors.
- Visualize flight routes and delays on maps.

## Requirements

- Python 3.x
- pandas
- matplotlib
- scipy
- Jupyter Notebook (optional)

## Getting Started

1. Clone the repository.
2. Install required libraries (`pip install pandas matplotlib scipy`).
3. Open the Jupyter Notebook file ("flights_analysis.ipynb").
4. Run the cells within the notebook to execute the Python code and view the visualizations.

## Contributing

We welcome contributions to expand and improve this project. Feel free to fork the repository, add your analyses, and submit pull requests.

This project provides a starting point for exploring flight data with Python. By building upon this foundation, you can delve deeper into various aspects of flight operations and uncover valuable insights.
