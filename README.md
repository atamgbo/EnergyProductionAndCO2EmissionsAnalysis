# World Energy and CO2 Emissions Analysis

## Introduction
This project is focused on analyzing energy consumption and CO2 emissions data to gain insights into global energy trends and its environmental impact. The project utilizes SQL to extract, transform, and analyze data from a database containing information on energy consumption, energy production, GDP, population, and CO2 emissions.

## Skills 
- SQL: Utilized SQL queries to extract and manipulate data.
- Data Analysis: Performed various analytical tasks, including trend analysis, comparative analysis, and correlation analysis.

## Analysis
The analysis performed in this project includes:

1. Trend Analysis: Calculating and visualizing the yearly trends in energy consumption, energy production, and CO2 emissions.
2. Correlation Analysis: Examining the relationships between energy consumption, GDP, population, and CO2 emissions using correlation coefficients.
3. Regional Analysis: Analyzing energy consumption, energy production, and CO2 emissions by regions to identify regional patterns and differences.
4. Country Analysis: Investigating the energy profiles, CO2 emissions, and energy intensity metrics for individual countries to identify notable cases and trends.

## Results
The key findings from the analysis include:

- Trend Analysis: The energy consumption and CO2 emissions have generally increased over the years, while energy production has shown some variations.
- Correlation Analysis: A positive correlation exists between energy consumption and CO2 emissions, with varying strengths across different countries.
- Regional Analysis: Regions with higher GDP tend to have higher energy consumption and CO2 emissions, but the intensity levels vary. The regions with the most O2 Emissions are Asia, Europe, and the Americas
- Country Analysis: Certain countries exhibit higher energy intensity or CO2 emissions, providing insights into potential areas for improvement and policy interventions.

## Code and Tables

### COLUMNS AND UNITS
Country, Energy Type, Year (1980 - 2019), Energy Consumption (quad Btu), Energy Production (quad Btu), Gross Domestic Product - GDP  (Billion 2015$ PPP), Population (MPerson), Energy_intensity_per_capita (MMBtu/person), Energy_intensity_by_GDP (1000 Btu/2015$ GDP PPP), and CO2 Emissions (MMtonnes CO2).

### WORLDWIDE ANALYSIS
#### World Energy and CO2 Emissions Data in the most recent year (2019)

![World2019](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-1.png)

![World2019 Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-2.png)

#### World Population and CO2 Emissions Data from 1980 to 2019

![World 1980 - 2019](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-3.png)

![World 1980 - 2019 Tablea](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-4.png)

![World 1980 - 2019 Tableb](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-5.png)

#### World Energy Consumption, Energy Production, and C02 emission for each energy type in the most recent year (2019)

![Energy Types](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-6.png)

![Energy Types Tables](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-7.png)

### TREND ANALYSIS

#### Year-on-Year World CO2 Emissions Difference, Percentage Difference, and their Averages
![YoY](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-8.png)

![YoY Tablea](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-9.png)

![YoY Tablea](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-10.png)

### CORRELATION ANALYSIS
#### Correlation Coefficients between energy consumption, GDP, population, and CO2 emissions

![Corr](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-11.png)

![Corr Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-12.png)

### REGIONAL ANALYSIS

#### Regional GDP, Population, Energy_consumption, Energy_production, and CO2 Emissions, Percentage of Total, ranked by CO2 Emissions in 2019

![Regional CO2](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-13.png)

![Regional CO2 Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-14.png)

#### Region by Energy_intensity_per_capita, Energy_intensity_by_GDP

![Regional Intensity](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-15.png)

![Regional Intensity Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-16.png)

### COUNTRY ANALYSIS

#### View a Particular country's energy and CO2 emissions data for the most recent year (2019). Nigeria and United States as examples

![View Country](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-17.png)

![View Country Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-18.png)

#### Top 10 Countries by GDP, Population, Energy_consumption, Energy_production, and CO2 Emissions, Percentage of Total, ranked by CO2 Emissions

![Country CO2](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-19.png)

![Country CO2 Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-20.png)

#### Top 10 Countries by Energy_intensity_per_capita, Energy_intensity_by_GDP

![Country Intensity](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-21.png)

![Country Intensity Table](https://github.com/atamgbo/EnergyProductionAndCO2EmissionsAnalysis/blob/main/EPCO2-22.png)


## Usage and Future Work
This project can serve as a starting point for further analysis and exploration of energy and CO2 emissions data. The SQL code provided can be modified and expanded to incorporate additional analysis or explore specific research questions.

Possible future work includes:
- Deepening the regional and country-level analysis to identify specific factors contributing to energy consumption and CO2 emissions.
- Conducting predictive modeling to forecast future energy trends and evaluate the effectiveness of potential mitigation strategies.
- Exploring additional data sources and integrating external datasets to enrich the analysis and provide a more comprehensive understanding of the energy landscape.

## Conclusion
This project showcases the utilization of SQL for analyzing energy consumption and CO2 emissions data. Through various analyses, insights into global energy trends, correlations, and regional disparities can be obtained. The project serves as a foundation for further exploration and research in the field of energy and environmental analysis.
