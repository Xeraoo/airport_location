# Analysis for Optimal Airport Location Based on Given Criteria [5C]

## Overview

This project focuses on identifying the best possible location for constructing an airport in Poland, specifically by analyzing vector data and applying spatial criteria. The analysis was performed in QGIS, using multiple layers and conditions to narrow down suitable regions. The goal was to find a county that meets all the defined spatial and demographic criteria while being logistically feasible.

## Maps and Analysis

### 1. **Initial Data Loading and Symbolization**
   - **Description**: This map displays all airports, major roads, and county boundaries in Poland. Airports are symbolized with blue squares.
   - **Purpose**: The initial setup for visualizing important infrastructure and spatial extents.

### 2. **Counties with Populations Over 90,000**
   - **Description**: This map shows counties (powiaty) with populations exceeding 90,000 inhabitants, highlighted in pink. The Balice and Okęcie airports are also marked.
   - **Purpose**: To prioritize regions with higher populations, which could provide a demand base for the airport.

### 3. **Buffer Zone Around Airports**
   - **Description**: A 100 km buffer zone is drawn around the Balice and Okęcie airports.
   - **Purpose**: To eliminate counties too close to these major airports, ensuring that the new airport won't interfere with the existing infrastructure.

### 4. **Counties Outside the 100 km Buffer**
   - **Description**: This map highlights counties that fall outside the 100 km buffer zones around the selected airports.
   - **Purpose**: To focus on regions that are far enough from existing airports to warrant the construction of a new one.

### 5. **Counties in the Świętokrzyskie Voivodeship**
   - **Description**: The map highlights counties in the Świętokrzyskie Voivodeship, with a focus on the Starachowicki and Ostrowiecki counties.
   - **Purpose**: Narrowing down the selection to a specific voivodeship for further analysis.

### 6. **Buffer Based on the E77 Road and Counties Starting with 'S'**
   - **Description**: A buffer zone is drawn around the E77 highway, and counties starting with the letter "S" are highlighted.
   - **Purpose**: To ensure that the selected county has easy access to major transportation routes.

### 7. **Final County Selection**
   - **Description**: The final map shows that **Powiat Starachowicki** is the optimal location based on all the set criteria.
   - **Purpose**: To finalize the county meeting all specified requirements for population, proximity to infrastructure, and strategic location.

## Criteria Used

1. **Population**: Counties with over 90,000 inhabitants.
2. **Proximity to Existing Airports**: Counties outside a 100 km buffer from Balice and Okęcie airports.
3. **Regional Focus**: Preference for counties in the Świętokrzyskie Voivodeship.
4. **Access to Major Roads**: Counties near the E77 road were prioritized.
5. **County Name**: Counties starting with the letter "S" were specifically analyzed.

## Tools and Software

- **QGIS**: All spatial data analysis and map production were performed using QGIS.
- **Geospatial Data**: Population data, county boundaries, airport locations, and road networks were used to conduct the analysis.

## Map

![image](https://github.com/user-attachments/assets/344b543b-8050-4c48-ae87-639d3a11566b)

