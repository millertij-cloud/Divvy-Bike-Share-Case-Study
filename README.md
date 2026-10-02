# Divvy-Bike-Share-Rider-Behavior-Analysis
## Overview
This end-to-end data analytics case study examines how casual riders and annual memebers use Divvy bike-share services differently. The goals was to identify behavior patterns that could inform strategies to encourage casual rider to convert to annual memberships. 

## Business Question
How do casual riders and annual members differ in trip volume, trip duration, weekday usage, hourly usage, and top starting stations?

## Tools Used
- Google BigQuery and GoogleSQL
- R and RStudio
- RMarkdown
- Tableau Public
- Microsoft Excel

## Dataset
- ** Source:** Divvy/Cyclistic historical trip data
- ** Scope:** [months and year analyzed]
- ** Full cleaned dataset:** Approximately [final number] trip-level records
- ** Analysis population:** Approximately [final valid-trip count] valid trips after applying the documented duration rule

  The raw source files are not included in this repository. The dataset is publicly available from [source link]. This repository includes the SQL, RMarkdown analysis, dashboard screenshots, and documentation needed to understand the workflow.

## Data Preparation and Validation
1. Combined and standardized monthly trip data in Google BigQuery.
2. Cleaned timestamps, trip-duration fields, rider-type values, and station fields.
3. Checked for missing values, duplicate records, invalid durations, and inconsistent data types.
4. Applied a documented valid-trip rule: trip duration greater than 1 minute and less than or equal to 240 minutes.
5. Validated record counts, average trip duration, rider-type totals, and top-station results across BigQuery, R, and Tableau.

## Analysis
The analysis compared casual riders and annual members by:

- Number of trips
- Average trip duration
- Day-of-week usage
- Hour-of-day usage
- High-volume starting stations

## Key Findings
1. First final, evidence-based finding
2. second final, evidence-based finding
3. third final, evidence-based finding

## Recommendations
1. finding 1
2. finding 2
3. Optional finding 3

## Limitations
This dataset describes observed trip behavior. It does not include rider demographics, marketing exposure, reasons for riding, or actual membership-conversion outcomes. The analysis identifies patterns and opportunities for further testing; it does not prove that a particular campaign caused membership conversion. 

## Project Deliverables
- **SQL analysis:** [sql/divvy_anallysis.sql]
- **RMarkdown:** [r/divvy-Case-Study.Rmd]
- **Tableau dashboard:** [View the interactive Tableau Public dashboard] (https://public.tableau.com/views/AllDivvyRows/DIVVYRiders?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- **Dashboard screenshots:** [images]
- **Data documentation:** [data/README.md]

## Repository Structure

```text
divvy-bike-share-case-study/
├── sql/       # BigQuery SQL cleaning and analysis queries
├── r/         # RMarkdown analysis and visualization code
├── reports/   # Rendered analysis report
├── tableau/   # Tableau Public dashboard link
├── images/    # Dashboard and chart screenshots
└── data/      # Dataset source and data dictionary information
```
### Skills Demonstrated
SQL • Google BigQuery • Data Cleaning • Data Validation • Exploratory Data Analysis • R • RMarkdown • Tableau • Data Visualization • Dashboard Development • Data Storytelling • Business Recommendations
