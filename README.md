# Forecasting Global Population Trends

## Introduction
In this project, I explored global population data using Power BI. The goal was to analyze trends from 1960 to 2021 and use Power BI's forecasting tool to predict how the population might grow over the next 10 years.

## Steps

1. **Adding a Line Chart**  
   I started by opening the `WorldPopulation.pbix` file and added a line chart at the bottom of the report page. For the axes:
   - **X-axis:** `Year` (without date hierarchy).
   - **Y-axis:** `Population`.

   I resized the chart, updated the title to "World Population by Year," and used the **Format Painter** tool to make the style consistent with the rest of the report.

2. **Applying Forecasting**  
   I selected the line chart and enabled the forecasting option from the **Analytics** pane. Here’s what I set:
   - Forecast Length: **10 years**.
   - Confidence Interval: **95%**.  

   After applying the changes, I reviewed the forecast line and the insights it provided by hovering over the visualization.

3. **Customizing the Forecast Line**  
   To improve the look of the forecast, I made a few adjustments:  
   - Changed the line color.  
   - Set the transparency to 50% to highlight the projection.  
   - Modified the confidence band style to lines.  
   - Updated the tooltip title to "Population Forecast" for clarity.  

   This made the forecast both informative and visually cohesive with the rest of the report.

## Outcome
The final report not only shows historical population trends but also offers a clear forecast for the next decade. This predictive analysis adds a valuable forward-looking perspective to the report, making it a great tool for understanding global population growth.

## Visualization
- Placeholder for the forecast chart:

  ![Insert Forecast Chart Here](./World_population.png)
