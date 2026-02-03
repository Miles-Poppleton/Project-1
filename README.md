# Project-1 Scope of Work
Cive 202 Project 1

Scope of Work
Project Background

The UNMC Water, Climate and Health Group is a multidisciplinary research team studying the effects of environmental factors—including air quality—on human health. In partnership with AirPurple, UNMC has deployed air quality sensors throughout Nebraska to collect continuous measurements of particulate matter (PM2.5, PM10), volatile organic compounds (VOCs), and associated environmental variables.

Because air quality analysis is not a primary expertise of the current UNMC research team, UNMC issued a Request for Proposals (RFP) seeking qualified engineering consultants to analyze the AirPurple dataset collected from February 2024 through March 2025. [Your Engineering Firm] was selected to perform this analysis and prepare technical documentation and reporting to support UNMC’s research and decision-making needs.

Project Objectives

The objectives of this project are to:

Analyze air quality data collected from AirPurple sensors across Nebraska.

Identify locations with elevated concentrations of PM2.5, PM10, and VOCs.

Evaluate compliance with National Ambient Air Quality Standards (NAAQS).

Assess the influence of temperature, humidity, elevation, and geographic location on air quality.

Identify potential air quality “hotspots” that may pose public health risks.

Provide clear, reproducible analysis and documentation suitable for academic and professional review.



Scope of Services and Tasks

The consultant will complete the following tasks as part of this project:

Task 1: Data Acquisition and Preparation

Obtain AirPurple air quality data for Nebraska covering February 2024 to March 2025.

Compile raw datasets into CSV format suitable for analysis.

Perform data cleaning, including handling missing values, timestamps, and sensor identifiers.

Group all analyses by sensor name where applicable.

Task 2: Descriptive Statistical Analysis

Calculate mean and median concentrations of VOCs, PM2.5, and PM10 for each sensor location.

Identify the five (5) locations in Nebraska with the highest mean and median concentrations for each pollutant.

Task 3: Maximum Concentration Events

Identify maximum observed concentrations for VOCs, PM2.5, and PM10.

Determine the dates and sensor locations where these maximum values occurred.

Conduct preliminary research to propose potential causes (e.g., weather events, wildfires, agricultural activity, urban emissions).

Task 4: Environmental Influence Analysis

Categorize humidity levels as:

Low (<50%)

High (50–80%)

Very High (>80%)

Categorize temperature as:

Below Freezing (<32°F)

Cool (32–50°F)

Warm (51–70°F)

Hot (>70°F)

Analyze pollutant concentrations across humidity and temperature categories to evaluate their impact on air quality.

Task 5: AQI Health Risk Evaluation

Convert PM2.5 and PM10 concentrations to Air Quality Index (AQI) values using EPA guidelines.

Identify occurrences of AQI levels classified as “Unhealthy for Sensitive Groups.”

Document when and where these events occurred.

Investigate and discuss potential contributing factors based on publicly available data and EPA/AirNow resources.

# Summary
Air quality plays a significant role in public health, particularly through exposure to particulate matter (PM₂.₅ and PM₁₀) and volatile organic compounds (VOCs), which have been linked to respiratory and cardiovascular health impacts. To better understand air quality conditions across Nebraska, the UNMC Water, Climate and Health Group partnered with AirPurple to collect continuous air quality data using a network of low-cost sensors.

Because air quality analysis is not a primary expertise of the UNMC research team, an external engineering consultant was selected to analyze the AirPurple dataset collected between February 2024 and March 2025. The objectives of this project were to summarize spatial and temporal air quality patterns, assess compliance with National Ambient Air Quality Standards (NAAQS), identify potential air quality hotspots, and evaluate the influence of environmental factors such as temperature, humidity, and elevation.

- Methods

AirPurple sensor data for Nebraska were obtained through publicly available PurpleAir resources. The dataset included measurements of PM₂.₅, PM₁₀, VOCs, temperature, relative humidity, elevation, and sensor location. Data processing and analysis were conducted using Python in a Jupyter Notebook to ensure reproducibility.

Raw data were cleaned by removing incomplete records and standardizing timestamps. All results were grouped by sensor name where applicable. Mean and median concentrations of PM₂.₅, PM₁₀, and VOCs were calculated for each sensor, and the five locations with the highest values were identified. Maximum pollutant concentrations were also determined along with the dates and locations where they occurred.

Temperature and relative humidity were categorized using predefined ranges to evaluate their influence on air quality. PM₂.₅ and PM₁₀ concentrations were converted to Air Quality Index (AQI) values using EPA guidelines to identify periods of potential health concern. Sensor elevation was analyzed to explore its relationship with pollutant concentrations.

- Results and Discussion

Analysis of mean and median pollutant concentrations showed that a small number of sensor locations consistently reported higher levels of PM₂.₅, PM₁₀, and VOCs. These locations were generally associated with urban areas or regions influenced by transportation, industrial activity, or agricultural operations.

Maximum pollutant concentrations occurred on specific dates and at localized sensor locations, suggesting the influence of short-term events such as wildfire smoke transport, agricultural activity, temperature inversions, or increased local emissions.

Higher particulate matter concentrations were more frequently observed during periods of high and very high humidity, likely due to reduced atmospheric dispersion and particle growth. Temperature also influenced air quality, with elevated concentrations commonly occurring during cooler conditions when atmospheric mixing is limited.

Several instances of AQI levels classified as “Unhealthy for Sensitive Groups” were identified for PM₂.₅ and PM₁₀. These events were limited in duration but represent periods of increased health risk, particularly for vulnerable populations. Exploratory analysis suggested that lower-elevation sensors tended to report higher particulate matter concentrations, indicating that topography may play a role in pollutant accumulation.

- Conclusions

This project provides an overview of air quality conditions across Nebraska using AirPurple sensor data. While overall air quality generally met applicable standards, elevated pollutant concentrations were observed at select locations and during specific events. Environmental factors such as humidity, temperature, and elevation were found to influence measured air quality and should be considered in future monitoring efforts. These findings support continued air quality monitoring and targeted investigation of identified hotspots to better protect public health.

- References

AirPurple Map:  https://map.purpleair.com/air-quality-standards-us-epa-aqi?opt=%2F1%2Flp%2Fa10%2Fp604800%2FcC0#5.21/40.002/-97.008
Purple Air Community: https://community.purpleair.com/c/data/api/18 
EPA Air Quality Tables: EPA Air Quality Index Document.pdf
Air Now website: https://www.airnow.gov/

# Annotated Code Document

# Project 1 Raw Data
http://localhost:8888/lab/tree/Project%201%20Final%20Draft

