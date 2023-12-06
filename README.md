# Mobility-Based Transportation Patterns in Central London

## Introduction

This project presents a comprehensive analysis of mobility-based transportation methods in Central London, focusing on the year 2022. Using various datasets, the study explores relationships between transportation modes and societal factors, uncovering trends and patterns within London's streets.

## Data Sources

Data used in this study includes:

- `2022-Central.csv`: Records frequencies of different transportation modes.
- `0-Count locations.csv`: Details specific locations within London.
- Seasonal Datasets: `2022 Q1 (January-March).csv`, `2022-1-spring.csv`, `2022-2-autumn.csv`.

## Methodology

The analysis involved data cleaning, preparation, and visualization using Python, Pandas, and Plotly Express. Key steps included:

1. **Data Inspection**: Using `pandas.DataFrame.head()` and `pandas.DataFrame.dtypes`.
2. **Data Preparation**: Grouping and transforming data with `pandas.DataFrame.groupby()`.
3. **Visualization**: Creating visual representations with Plotly Express.

## Results

Key findings include:

- **Daily Commute Patterns**: Identified peak transportation times correlating with traditional rush hours.
- **Geospatial Mapping**: Revealed high-density transportation areas, particularly near the Thames River.
- **Seasonal Impact**: Analyzed the effect of weather on transportation demand, highlighting the influence of temperature over precipitation.

## Conclusion

The study provides insights into the dynamics of urban mobility in Central London, showing how transportation is influenced by and influences the environment and community. It offers a foundation for future research and development in urban transportation planning.


## Author
- Skye Chao

## Installation

To get started with this project, follow these steps to install the necessary components:

```bash
# Clone the repository
git clone https://github.com/skyeschao/londonMobilityTransport.git

# Navigate to the project directory
cd londonMobilityTransport

