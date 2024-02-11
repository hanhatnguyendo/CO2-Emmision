# Reporting CO2 Emission of Distribution Network 


## Overview:

This repository is dedicated to the "Reporting CO2 Emission of Distribution Network" project, a comprehensive initiative aimed at calculating and visualizing carbon emissions from the downstream distribution network of a company. The primary objective is to create a dashboard that provides insights into the environmental impact of the distribution processes.

## Project Components:
- **Calculation Methodology:** The project employs the GHG protocol Scope 3, Category 9, focusing on calculating CO2 emissions. The formula involves utilizing Emissions Factors and considers the quantity of goods sold, distance traveled in transport legs, and emission factors of transport modes or vehicle types.
- **Emissions Formula:** The calculated CO2 emissions for each order number (linked with a customer and a date) are derived using the formula: **∑ (quantity of goods sold (tonnes) × distance traveled in transport legs (km) × emission factor of transport mode or vehicle type (kg CO2e/tonne-km))**.

 The chosen formula offers a gross estimation of CO2 emissions, providing valuable insights without requiring an excessively granular level of transportation data.

## Dashboard Visualization:
The core outcome of this project is the development of a dashboard that visually represents the calculated CO2 emissions. This tool will enable stakeholders to gain a clear understanding of the environmental impact of the distribution network.


<img width="631" alt="Screenshot 2024-02-11 at 11 28 20" src="https://github.com/hanhatnguyendo/CO2-Emmision/assets/76510432/4ea2bc1a-fa27-4861-ae58-92e1cdf5770f">



