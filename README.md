# CFD-Trend-Power-BI

Project Overview
This project involves the computational fluid dynamics (CFD) analysis of a 2-stage compressor, followed by data visualization and analysis using Power BI. The goal is to understand key performance metrics such as pressure, temperature, efficiency, and velocity across different stages of the compressor. The insights derived from this analysis are visualized using various chart types in Power BI to aid in decision-making and performance optimization.

Dataset
The dataset used in this project contains 200 rows of synthetic data generated to simulate the operating conditions of a 2-stage compressor. The data includes the following columns:

Blade Position: The normalized position along the compressor blade (0 to 1).
Pressure: The pressure at each blade position, measured in Pascals.
Temperature: The temperature at each blade position, measured in Kelvin.
RPM: The rotational speed of the compressor, measured in revolutions per minute (RPM).
Efficiency: The efficiency of the compressor at various RPM levels, measured as a percentage.
Velocity: The velocity of the airflow, measured in meters per second.
Inlet Pressure: The pressure at the inlet of the compressor, measured in Pascals.
Mass Flow Rate: The mass flow rate of the air through the compressor, measured in kilograms per second.
Energy Loss Due to Friction: Energy loss attributed to friction within the compressor, measured in Joules.
Energy Loss Due to Heat: Energy loss attributed to heat generation, measured in Joules.
Energy Loss Due to Leakage: Energy loss attributed to leakage, measured in Joules.
Cumulative Efficiency Gain: The cumulative efficiency gain over time.
Cumulative Energy Loss: The cumulative energy loss over time.
Visualizations
The project includes several key visualizations created in Power BI:

Line Charts:

Pressure vs. Blade Position
Temperature vs. Blade Position
Efficiency vs. RPM
Bar Charts:

Efficiency Comparison Across Different RPM Levels
Average Pressure in Different Compressor Stages
Pie Charts:

Proportion of Pressure Zones
Energy Loss Distribution
Histograms:

Temperature Distribution
Velocity Distribution
Scatter Plots:

Mass Flow Rate vs. Inlet Pressure
Temperature vs. Pressure
Box Plots:

Velocity Distribution Across Different Blade Radii
Temperature Variability
Heatmaps:

Correlation Matrix
Pressure and Temperature Distribution Across Compressor
3D Surface Plots:

Temperature and Pressure Distribution
Velocity Profile
Area Charts:

Cumulative Energy Loss Over Time
Cumulative Efficiency Gain with RPM
Pareto Charts:

Factors Affecting Efficiency
How to Run the Project
Clone the Repository:

git clone https://github.com/username/repository-name.git
Navigate to the project directory.
Download the Dataset:

The dataset used for the analysis is available as CFD_PowerBI_Dataset.csv in the root directory.
Open in Power BI:

Import the dataset into Power BI Desktop.
Create the visualizations as described above.
Save and Share:

Save your work as a .pbix file to share with others or to present your findings.
Conclusion
This project demonstrates how CFD analysis data can be effectively visualized and analyzed using Power BI. By leveraging various chart types, the project provides insights into the performance of a 2-stage compressor, aiding in the understanding and optimization of its operation.
