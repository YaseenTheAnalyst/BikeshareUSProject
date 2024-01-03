# BikeShare Data Analysis

## Overview

This Python script leverages bike-sharing data from three cities: Chicago, New York City, and Washington, providing users with insights into various aspects of the bike-sharing programs. The analysis includes statistics on popular times of travel, common stations and trips, trip durations, and user demographics.

## Process

1. **User Input:**
   - The script begins by prompting the user to select a city from the available options: Chicago, New York City, or Washington.
   - Users are then asked to specify the month and day they would like to explore or can choose to analyze data for all months or days.

2. **Data Loading and Preprocessing:**
   - The selected city's data is loaded from the corresponding CSV file.
   - The script preprocesses the data, converting 'Start Time' to datetime and extracting additional time-related features (month, day, hour).

3. **Statistical Analysis:**
   - The script calculates and displays the most common month, day, and hour of travel based on the user's input.
   - It identifies the most frequently used starting and ending stations, as well as the most common trip combination.

4. **Trip Duration Analysis:**
   - The script provides insights into the total and average trip duration, presenting the results in both seconds and converted to days or minutes for better readability.

5. **User Demographics:**
   - The script showcases user statistics, including the count of different user types (e.g., Subscribers, Customers) and, for cities other than Washington, the earliest, most recent, and most common birth years, along with gender distribution.

6. **Interactive Data Viewing:**
   - Users have the option to view 5 rows of individual trip data at a time, allowing for a more detailed exploration of the dataset.

7. **Restart Option:**
   - After completing the analysis, users can choose to restart the process or exit the script.

## Conclusion

This script provides a comprehensive analysis of bike-sharing data, offering users valuable insights into usage patterns and user demographics. The modular structure allows for easy extension and adaptation for future enhancements or additional features.

