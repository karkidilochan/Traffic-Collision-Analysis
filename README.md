# Traffic Collision Analytics: A Data-Driven Approach to Road Safety

## Project Overview

This data engineering project performs comprehensive analytics on traffic accident datasets to enhance road safety through data-driven insights. The project analyzes over 7 million traffic accident records across the United States from 2016 to 2023.

## Key Features

- **Comprehensive Data Sources**
  - US-Accidents national dataset (2016-2023)
  - Localized datasets for New York City and Chicago
  - Over 7 million accident records analyzed

- **Advanced Data Engineering Techniques**
  - Distributed computing with Apache Spark
  - Distributed storage using HDFS
  - Efficient data processing with Scala and SparkSQL
  - Data caching using Apache Parquet

## Research Questions

### When Do Accidents Happen?
- Analysis of accidents by:
  - Day of the week
  - Month
  - Year
  - Weather conditions
  - Wind and temperature properties

### Where Do Accidents Happen?
- Detailed geospatial analysis including:
  - State-level accident distribution
  - City-level accident hotspots
  - Interstate accident heatmaps
  - Specific location analyses (Colorado, Denver, Fort Collins)

## Visualization Techniques

- Mapping and visualization using:
  - Folium
  - Matplotlib
  - Seaborn
  - KeplerGL

## Technical Highlights

- **Technology Stack**
  - Apache Spark
  - Scala
  - SparkSQL
  - HDFS
  - Python (Pandas, Matplotlib)

- **Data Optimization Strategies**
  - Git Large File Storage (LFS)
  - Parquet file format with gzip compression
  - In-memory dataframe caching

## Key Insights

- Comprehensive analysis of traffic accident patterns
- Identification of high-risk locations and conditions
- Benchmarked query performance across different datasets

## Potential Impact

Valuable for:
- Urban planners
- Transportation engineers
- Policy makers
- Researchers in geospatial analysis and data science

## Repository Structure

```
traffic-collision-analytics/
│
├── data/
│   ├── us-accidents/
│   ├── nyc-accidents/
│   └── chicago-accidents/
│
├── src/
│   ├── data_collection/
│   ├── data_exploration/
│   ├── distributed_analytics/
│   └── visualization/
│
├── notebooks/
│   ├── eda.ipynb
│   └── spark_analysis.ipynb
│
└── README.md
```

## Getting Started

1. Clone the repository
2. Install dependencies
3. Set up Spark and HDFS
4. Run data exploration notebooks
5. Execute distributed analytics scripts


## Contributors

- Dilochan Karki
- Yunik Tamrakar
```
