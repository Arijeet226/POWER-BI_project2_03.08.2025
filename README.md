# POWER-BI_project2_03.08.2025
This is my first power bi project on live data made interactive dashboard from live data fetched from weatherapi.com
Real-Time Live Weather Dashboard Project - Roadmap
Overview
This project creates an interactive, real-time weather dashboard using Power BI that fetches live weather data from a weather API. It helps users monitor current weather conditions, forecasts, and air quality indicators for multiple cities with dynamic visuals and automated updates.

Roadmap
## 1. Data Source and API Setup
Choose the Data Source: Instead of using static CSV files, this project uses a Weather API to fetch live, up-to-date weather data.

What is an API?
An API (Application Programming Interface) is a service that provides data hosted by someone else. You send requests, and get responses in formats like JSON or XML.
Register for API Access:
Sign up on the weather API provider website.
Obtain your unique API key/token for authentication.
Note API usage limits (e.g., 100 free requests per day).

## 2. Accessing and Loading Data into Power BI
Connect Power BI to the API:
Use Power BI’s “Get Data” feature with Web connector.
Input the API URL including your API key and query parameters (city name, forecast days, etc.).
Parse the JSON Data:
Expand the JSON data into tables using Power BI’s Power Query Editor.
Organize data into related tables such as:
Current Weather Data
Forecast Data (by day and by hour)
Location Data

## 3. Data Preparation and Modeling
Clean & Format Data:
Remove unnecessary columns and tables to keep the model light.
Rename columns for clarity.
Create Relationships:
Link tables via keys like city ID or date/time fields.
Create Calculated Columns and Measures:
Examples include temperature conversion, average humidity, weather condition labels, air quality index calculations, etc.

## 4. Building the Dashboard Visuals
Add Visual Elements:
Cards and KPIs for current temperature, humidity, wind speed, pressure, AQI.
Line charts for temperature and forecast trends.
Tables or slicers to select cities dynamically.
Enhance User Experience:
Apply conditional formatting (e.g., color code AQI).
Use icons and shapes to represent weather conditions visually
Format dates and times for readability (including sunrise and sunset).

## 5. Advanced Features
Data Refresh Setup:
Configure Power BI to refresh data automatically or on demand, allowing real-time updates.
Handle API Limits and Data Merging:
Combine weather data of multiple cities into a master table.
Implement error handling or retries to respect API usage policies.

## 6. Styling and Finishing Touches
Theme and Background:
Apply a professional dark theme for better visuals.
Use custom images and icons as background or decorative elements.

## Final Testing:
Verify responsiveness of visuals when data updates.
Check accuracy of measures and filters.
## Outcome
At the end of this project, you will have a fully functional, real-time weather dashboard that:
Displays accurate current and forecasted weather data for multiple cities.
Updates automatically with fresh data from the API.
Uses clear visual cues to convey weather insights and alerts.
