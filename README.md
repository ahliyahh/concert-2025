# Concert Attendance Analysis

## Overview

A personal data analysis project exploring concert attendance patterns across artists, venues, and years. The project combines a small SQL-based data collection exercise with Python data cleaning, aggregation, and visualization.

## Questions explored

- Which artists appear most frequently in the attendance records?
- Which venues appear most frequently?
- How does the number of recorded concerts vary by year?

## Data

The notebook analyzes a personal attendance dataset with artist, venue, and date fields. The records span multiple years, including 2025. The data was initially stored in a SQL table and exported to CSV for analysis.

## Methods

1. Load the exported records into pandas.
2. Standardize column names and parse the date field.
3. Exclude records whose dates could not be parsed.
4. Aggregate attendance counts by artist, venue, and year.
5. Use Matplotlib to create bar charts and a time-series plot.

## Tools

- SQL
- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Limitations and next steps

This is a personal dataset, not a representative sample of concert attendance generally. The notebook also encounters inconsistent date formats and at least one invalid date value, which is excluded during date cleaning. A future revision could standardize date formats at the data-entry stage, document the SQL schema, and include a compact summary table alongside the visualizations.

