# Cyclistic Bike-Share Analysis

## Project Overview

This project explores bike-share usage patterns for Cyclistic, a fictional bike-sharing company, to identify differences in how annual members and casual riders use the service.

The primary business objective is to understand how casual riders and annual members interact with the bike-sharing service and identify potential opportunities to convert casual riders into annual memberships.

Using Python, I performed data cleaning, data transformation, exploratory data analysis, and statistical comparisons to uncover differences in riding behaviour.

## Business Task

How do annual members and casual riders use Cyclistic bikes differently?

The analysis focuses on identifying usage patterns based on:
- Number of rides
- Average ride duration
- Day of the week
- Differences in weekday and weekend usage

The findings can help inform targeted marketing strategies aimed at increasing annual memberships.

## Tools & Technologies

- **Python:** Primary programming language
- **Pandas:** Data manipulation, cleaning, and aggregation
- **Jupyter Notebook:** Analysis and documentation
- **Data Analysis:** Exploratory analysis and statistical summaries

## Data Preparation & Cleaning

The analysis began with approximately 791,956 ride records.

The data preparation process included:

1. Reviewing the dataset structure, column names, data types, and descriptive statistics.
2. Standardizing rider classifications by combining the `Subscriber` and `member` categories and the `Customer` and `casual` categories.
3. Converting ride start and end timestamps into datetime formats.
4. Creating additional variables, including ride duration, date, month, year, and day of the week.
5. Removing invalid ride records, including negative ride durations and records associated with maintenance or quality checks.

After cleaning, the analysis contained 788,189 ride records.

## Exploratory Data Analysis

I investigated differences between annual members and casual riders using descriptive statistics and grouped aggregations.

Key areas of investigation included:

- Average and median ride duration by rider type.
- Total ride counts by rider type.
- Ride frequency across weekdays.
- Average ride duration across weekdays.
- Comparisons of weekday and weekend usage patterns.

## Key Findings

**1. Casual riders take longer rides.**

Casual riders had an average ride duration of approximately 89.5 minutes, compared with approximately 13.3 minutes for annual members.

**2. Casual riders demonstrate stronger weekend usage.**

Saturday and Sunday showed the highest casual rider volumes, suggesting a stronger association with weekend riding.

**3. Annual members demonstrate stronger weekday usage.**

Annual members recorded their highest ride volumes during the working week, particularly Tuesday through Thursday.

**4. Different rider groups demonstrate different usage behaviours.**

The differences in ride frequency and duration suggest that casual riders and annual members may have different motivations and usage habits.

## Business Recommendations

Based on the observed usage patterns, potential strategies to explore include:

- Developing weekend-focused membership promotions to engage casual riders.
- Highlighting the convenience and potential value of annual memberships to frequent casual riders.
- Testing targeted marketing campaigns around periods of high casual rider activity.
- Evaluating conversion rates to determine which promotional strategies are most effective.

These recommendations would require further testing and customer conversion data to measure their impact.

## Conclusion

This project demonstrates how exploratory data analysis can be used to investigate customer behaviour and identify potential business opportunities.

By cleaning, transforming, and analyzing nearly 800,000 ride records, I identified meaningful differences between annual members and casual riders.

The project strengthened my practical experience with Python, Pandas, data preparation, exploratory analysis, and translating analytical findings into business-focused recommendations.

## Skills Demonstrated

Python | Pandas | Data Cleaning | Data Wrangling | Exploratory Data Analysis | Descriptive Statistics | Data Aggregation | Business Analysis

# Data Sources

This project uses publicly available historical Divvy bike-share trip data.

**Source:** [Divvy Historical Trip Data](https://divvy-tripdata.s3.amazonaws.com/index.html)

**Datasets used:**
- `Divvy_Trips_2019_Q1_csv.csv` – First quarter of 2019
- `Divvy_Trips_2020_Q1_csv.csv` – First quarter of 2020

The original CSV files are not included in this repository because of their file sizes.

To reproduce the analysis:
1. Visit the official Divvy historical trip data archive.
2. Download the corresponding 2019 Q1 and 2020 Q1 ZIP files.
3. Extract the CSV files.
4. Place both CSV files in this `data` folder.
5. Run the Jupyter Notebook.

The data is provided publicly by Divvy and is subject to its [Data License Agreement](https://divvybikes.com/data-license-agreement).

