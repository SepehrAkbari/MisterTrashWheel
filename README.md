# Baltimorians & Their Trash
###### An analysis of litter collection data from the Mr. Trash Wheel in Baltimore's Inner Harbor

Welcome to the **MrTrashWheel-Analysis** project! This repository contains a detailed analysis of litter collection data from the Mr. Trash Wheel in Baltimore's Inner Harbor. The aim of this project is to understand seasonal patterns, the impact of specific events, and general trends in waste composition. Insights from this analysis can inform waste management strategies and environmental efforts in Baltimore and potentially other urban areas.

## Project Overview

Mr. Trash Wheel is a unique initiative in Baltimore, Maryland, designed to collect trash from the Inner Harbor using a combination of solar and hydro power. This project explores data collected by Mr. Trash Wheel to investigate:
- Seasonal and event-based changes in litter volume and composition
- Year-over-year patterns in trash collected
- Trends in specific waste types (e.g., cigarette butts, plastic bottles) over time

The project aims to answer key questions about Baltimore’s littering behavior and provide insights for targeted environmental action.

## Table of Contents
- [Data](#data)
- [Project Objectives](#project-objectives)
- [Analysis Summary](#analysis-summary)
- [Requirements](#requirements)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Data

The data used in this project is sourced from the Baltimore Waterfront Partnership’s Mr. Trash Wheel initiative. It includes records of trash collected in different categories, recorded over several years, with information on specific dates, trash types, and seasonal contexts.

Key features of the dataset:
- **Date** of collection
- **Trash type** (e.g., plastic bottles, cigarette butts, Styrofoam)
- **Volume** of each type collected
- **Event information** (e.g., holidays) and **seasonal** classification

## Project Objectives

1. **Seasonal Patterns**: Determine how trash volume and composition change seasonally.
2. **Holiday and Event Impact**: Analyze whether specific events or holidays, like July 4th or Christmas, influence the amount of litter collected.
3. **Trend Analysis**: Explore trends in trash collection over multiple years, focusing on specific types of waste.
4. **Insights for Action**: Provide insights that can help in designing effective waste management policies.

## Analysis Summary

This project includes the following key analyses:

- **Trash Composition by Season**: Identifies which trash types are most prevalent in different seasons.
- **Holiday and Weekend Impact**: Compares trash volumes on holidays and weekends against regular weekdays.
- **Year-Over-Year Changes**: Investigates changes in littering behavior from year to year, highlighting any significant trends.
- **High-Impact Waste Types**: Focuses on specific waste types (e.g., cigarette butts, plastics) that could be prioritized for intervention.

Each analysis includes plots, numeric summaries, and explanations of the data wrangling steps taken to answer specific questions.

## Requirements

This analysis is implemented in **R**, and the following packages are required:
- `tidyverse`
- `lubridate`
- `ggplot2`

You can install these packages using the following command:
```r
install.packages(c("tidyverse", "lubridate", "ggplot2"))
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/SepehrAkbari/MrTrashWheel-Analysis.git
```

2. Open the project in your preferred R environment.

3. Run the scripts in order as outlined in the Analysis folder.

Each script includes detailed comments to guide you through the data cleaning, wrangling, and visualization processes.

## Results

This project includes the following results:

1. Seasonal Analysis: Visualizations showing which seasons and holidays see higher litter volumes.
2. Trash Type Trends: Insights into specific waste types and their seasonality.
3. Impact Insights: Recommendations for targeted waste management strategies based on findings.

Sample results and key findings are presented in the Results folder.

## Contributing

Contributions to this project are welcome! If you would like to contribute, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

###### Fall 2024.