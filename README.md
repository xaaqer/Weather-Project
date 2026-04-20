# Weather-Project

**Overview**

This project implements a simple ETL data pipeline that integrates weather data from an external API into a structured data environment for analysis and visualization.

The pipeline connects:
OpenWeather API → MS SQL Server → Power BI

**Key Features**

- Building an end-to-end ETL pipeline from scratch
- Extracting data from the OpenWeather API using Python
- Transforming raw JSON data into a structured format
- Loading data into a Microsoft SQL Server database
- Connecting SQL database to Power BI for reporting
- Creating data visualizations and dashboards
- Preparing the pipeline for automated data refresh

**Technologies Used**

Python (requests, data processing)
MS SQL Server
Power BI
OpenWeather API
Git / GitHub

**Data Pipeline Flow**

1. Extract
- Fetch weather data from OpenWeather API
2. Transform
- Parse JSON response
- Select relevant fields (temperature, humidity, wind, etc.)
- Convert timestamps to readable format
3. Load
- Insert processed data into MS SQL database
4. Visualization
- Connect Power BI to SQL
- Build dashboards and reports

**Example Data**

The pipeline processes data such as:

- City
- Temperature
- Humidity
- Weather description
- Wind speed
- Cloud coverage
- Timestamp

**Future Improvements**

- Automating pipeline execution (Task Scheduler / cron)
- Adding more cities and historical data
- Implementing data validation and error handling
- Extending analysis in Power BI



