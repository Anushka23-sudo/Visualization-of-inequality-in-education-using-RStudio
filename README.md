# Visualization-of-inequality-in-education-using-RStudio
Overview
This repository contains an R Markdown script for generating an interactive dashboard that visualizes and explores global education inequality. The dashboard utilizes the flexdashboard framework along with popular R packages such as ggplot2, dplyr, reshape2, and plotly to create a variety of visualizations.

Key Features
Human Development Group Distribution: Explore the distribution of countries across different Human Development Groups using bar and pie charts.

Country-Specific Visualization: Dynamic rendering of bar plots based on user-selected Human Development Group, showing HDI ranks of countries.

Choropleth Map: Visualize HDI ranks of countries in 2021 on an interactive choropleth map.

Percentage of Inequality Over Years: Scatter plot depicting the percentage of inequality in education over time.

Change in Inequality (Pre and Post-Covid): Explore how inequality in education changed from 2019 to 2021 with an interactive scatter plot.

Inequality Comparison Across Years: Box plots comparing inequality in education for various years and additional bar plots for top and bottom countries.

3D Scatter Plot: Interactive 3D scatter plot visualizing inequality in education across different years, color-coded by the Human Development Index.

Scatter Plot of ISO3, Country, and UNDP Developing Region: Another 3D scatter plot illustrating the relationship between ISO3, Country, and UNDP Developing Region.

Inequality for Selected Year: Dynamic rendering of a bar plot based on user-selected country and year.

Legend for Development Group Colors: A legend for interpreting colors representing Human Development Groups.

Correlation Heatmap: Heatmap illustrating the correlation matrix between different indicators of inequality in education.

Getting Started
Ensure you have R and RStudio installed on your machine.
Clone this repository.
Open the R Markdown script (code.Rmd) in RStudio.
Install required R packages if not already installed (flexdashboard, ggplot2, dplyr, reshape2, plotly).
Run the script to generate the interactive dashboard.
Data
Make sure to have the dataset (dataset.csv) available at the specified file path in the script.
