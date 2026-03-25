# Contributing log for Final Project Presentation for AD450, Data Science Development

## Elton

- EDA
  - Histograms for latitude
- Data Cleaning and Transformation
  - Filling null values for country
  - Filling continent values from country codes
- Data Joining
  - Merged both dataframes together into one
- Data Visualization
  - Compare country and sig
- Aggregation and Grouping Operations
  - Grouping was done for Data Visualization step

## Bea

- EDA
  - Counts of alert levels.
  - Averages of earthquake statistics.
  - Counts of all null values
- Data Cleaning and Transformation
  - Modifying null values of alert levels
- Data Joining
  - Concatinated both earthquake datasets
  - Create concat with location, alert levels, depth and magnitude
- Data Viualization
  - What are alert levels based on region? Used a stacked bar chart
- Aggregation and Grouping Operations
  - Counts of alert levels grouped by continent

## Joe

- EDA
  - Chart with correlationd between depth and magnitude
- Data Cleaning and Transformation
  - Drop country and continent columns
- Data Joining
  - Create concat with depth, magnitude, date/time
- Data Viualization
  - Chart showing correlation between nst (number of stations used to to determine location) and magnitude
- Aggregation and Grouping Operations
  - TBD

## Kainen

EDA:
Correlation heatmap of all numeric columns to identify relationships

Data Cleaning and Transformation:
Added a new derivative magnitude category column bucketing magnitude values into various tiers

Data Joining:
Concatenated cdi, mmi, tsunami, and sig into a focused seismic impact dataframe

Data Visualization:
Seasonal patterns in earthquake activity by month showing count and average magnitude
Tsunami impact comparison showing CDI, MMI, and significance scores between tsunami and non-tsunami events
Tsunami risk by magnitude category showing number of tsunamis per severity tier with occurrence rate


Aggregation and Grouping Operations

Pivot table of mean magnitude and mean depth broken down by magnitude category and alert level
Aggregated CDI and MMI grouped by tsunami flag to compare felt vs measured intensity
Counted earthquake frequency and average magnitude grouped by month for seasonal analysis
Summarized seismic impact metrics comparing tsunami vs non-tsunami events across CDI, MMI, and sig

## Additional Contributions

- Construction of [CONTRIBUTING.md](CONTRIBUTING.md): Elton and Joe 
- Construction of [READ.md](READ.md): Bea and Elton
* Presentation Slides:
        Bea: (1-4,7-8,12-13)
        Elton:(6,9)
        Joe:(5)
        Kainen: (3,10-11)
