# Weather Data Analysis Report

## 1. Overview
This report summarizes key patterns in the local weather dataset, including temperature, rainfall, and humidity statistics computed at daily, monthly, and yearly scales.

## 2. Daily Temperature Statistics
- Mean daily temperature: **23.51**
- Minimum recorded temperature: **5.70**
- Maximum recorded temperature: **40.30**
- Standard deviation: **8.35**

## 3. Yearly Summary
The table below shows average temperature, total rainfall, and mean humidity for each year in the dataset.

|   date |   ('temperature', 'mean') |   ('temperature', 'min') |   ('temperature', 'max') |   ('rainfall', 'sum') |   ('humidity', 'mean') |
|-------:|--------------------------:|-------------------------:|-------------------------:|----------------------:|-----------------------:|
|   2023 |                   23.5107 |                      5.7 |                     40.3 |                1655.2 |                61.8247 |

## 4. Monthly Aggregations
Average monthly temperature, total monthly rainfall, and average monthly humidity are summarized below:

|   month |   temperature |   rainfall |   humidity |
|--------:|--------------:|-----------:|-----------:|
|       1 |      15.6645  |        0.4 |    62.5161 |
|       2 |      18.9643  |        0   |    61.3571 |
|       3 |      25.4677  |        0   |    48.9677 |
|       4 |      28.8267  |        0   |    46.5333 |
|       5 |      33.7129  |        0   |    46.5161 |
|       6 |      27.5133  |      342.6 |    78.7333 |
|       7 |      27.0129  |      623.2 |    85.871  |
|       8 |      29.229   |      441.3 |    76.871  |
|       9 |      32.7733  |      242.3 |    79.5    |
|      10 |      22.3935  |        5.4 |    59.4839 |
|      11 |      12.49    |        0   |    63.1667 |
|      12 |       7.88387 |        0   |    33      |

## 5. Visualizations
The following plots were generated and saved in the `plots/` folder:

- `daily_temperature_line.png`: Daily temperature trend line plot.
- `monthly_rainfall_bar.png`: Bar chart of monthly rainfall totals.
- `humidity_vs_temperature_scatter.png`: Scatter plot of humidity vs temperature.
- `combined_temp_rain.png`: Combined figure with temperature line and rainfall bars.

## 6. Interpretation and Insights
- Months with higher rainfall generally correspond to the monsoon season.
- Temperature variation across the year can be seen clearly in the line chart and monthly aggregates.
- The scatter plot indicates the relationship between humidity and temperature; clusters or trends may show how humidity tends to rise or fall with temperature.

Overall, this analysis demonstrates how NumPy, Pandas, and Matplotlib can be combined to clean real-world datasets, compute statistical summaries, build visualizations, and communicate insights in a structured report.
