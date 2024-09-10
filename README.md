# Weather Data Exploration using Jupyter

This project focuses on analyzing weather data using Python and Jupyter Notebook. The dataset includes various attributes such as wind speed, temperature, humidity, visibility, and pressure. The aim is to answer specific analytical questions related to the weather conditions.

## Project Objective

The goal of this project is to analyze weather data and answer the following questions through data exploration and statistical computations:

### Analysis Questions:
1. **Unique values in "Wind Speed"**  
   Identify all unique wind speed values recorded.

2. **Number of times when the Weather was exactly Cloudy**  
   Find how many times the weather condition was marked as "Cloudy".

3. **Rename the column 'Weather' to 'Weather Condition'**  
   Modify the column header for better understanding.

4. **The Mean of Visibility**  
   Calculate the mean (average) of visibility.

5. **The Standard Deviation of Pressure**  
   Compute the standard deviation of pressure.

6. **The Variance of Relative Humidity**  
   Determine the variance in the relative humidity data.

7. **All instances when Snow was recorded**  
   Retrieve all instances where snow was recorded.

8. **Minimum and Maximum value of each column against each Weather Condition**  
   Calculate the minimum and maximum values of each attribute for every weather condition.

9. **All instances when the Weather is Clear or Visibility is above 40**  
   Get all data entries where the weather is clear or visibility is more than 40 units.

10. **All instances where the Weather is Clear and Relative Humidity is greater than 50 or Visibility is above 40**  
    Retrieve instances where the weather is clear with relative humidity above 50% or visibility is more than 40 units.

## Dataset

The dataset used for this analysis contains the following columns:
- **Date/Time**: Date and time of the observation.
- **Temperature**: Temperature in degrees.
- **Dew Point**: Dew point temperature.
- **Humidity**: Percentage of humidity.
- **Wind Speed**: Wind speed in distance units.
- **Visibility**: Visibility in distance units.
- **Pressure**: Atmospheric pressure in standard units.
- **Weather Condition**: Description of weather conditions (e.g., Cloudy, Clear, Snow, etc.).

## Key Insights

- **Unique Wind Speeds**: The dataset contains several unique wind speed values, which reveal variations in the wind's intensity across different weather events.
- **Cloudy Weather Frequency**: The dataset helps in identifying how often the weather was exactly "Cloudy."
- **Visibility**: The average visibility provides a general idea of how far one could see during different weather conditions.
- **Pressure & Humidity Variations**: Calculating the standard deviation of pressure and variance in humidity helps in understanding the fluctuations in these parameters.

## Technologies Used

- **Python**: Main programming language for data manipulation and analysis.
- **Pandas**: Used for handling and processing the dataset.
- **Jupyter Notebook**: For an interactive environment to perform the analysis.
- **NumPy**: Utilized for numerical operations like mean, standard deviation, and variance.
