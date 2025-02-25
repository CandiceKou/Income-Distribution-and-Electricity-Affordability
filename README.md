# Income-Distribution-and-Electricity-Affordability
This repository contains a simulated income distribution for 48 Sub-Saharan African (SSA) countries and an estimated electricity affordability for residents in each country. The code supports the study published in "Assessing Grid Affordability for Universal Electricity Access in Sub-Saharan Africa."

## Scripts
- ***Electricity_Tariff_Calculator.xlxs:***
  This database includes the latest residential electricity tariffs for 48 SSA countries and estimates monthly electricity bills based on the Multi-Tier Framework (MTF).
- ***Summary_Electricity_Bills.xlxs:***
  This dataset contains the calculated monthly residential electricity bills for each tier across 48 SSA countries, standardized to 2024 US dollars.
- ***Data input.xlxs:***
  This dataset compiles raw data, including the GINI index, Gross National Income (GNI) per capita, the 2024 population for each country, and monthly electricity bills (in US dollars) for each tier.
- ***Code.ipynb:***
  This notebook utilizes the input dataset "Data_Input.xlsx" to simulate income distribution and calculate residential electricity affordability. Affordability is assessed by expressing monthly electricity bills (in US dollars) as a share of income.
- ***Country_Affordability_Results.xlsx:***
  This Excel sheet presents the results generated from the income simulation model and electricity affordability calculation.
- ***Actual_Residential_Electricity_Consumption.xlsx:***
  This dataset integrates and calculates actual residential electricity consumption across SSA countries. The International Energy Agency (IEA) provides total residential electricity consumption data for 32 countries. To estimate household electricity consumption, total residential consumption is divided by the population size and then multiplied by the average household size (number of people per household). For the remaining 16 countries where IEA data is unavailable, electricity consumption per capita is sourced from Index Mundi. Household electricity consumption is derived by multiplying per capita electricity consumption by the average household size (number of people per household). This dataset is used for comparison in the publication's result "Affordability vs. Actual Demand" section.

## Queries

For any queries or feedback. Kindly contact:
Yidan Kou: yidan.kou@eng.ox.ac.uk
