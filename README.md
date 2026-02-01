Concert Attendance Analysis
Overview
This project analyzes personal concert attendance data to explore trends across artists, venues, and time. The goal was to practice data cleaning, aggregation, and visualization using Python while answering clear, real-world analytical questions.
The dataset was originally stored in a SQL table and exported to CSV to allow for reproducible, recruiter-friendly analysis without requiring database setup.

Questions Explored
How many concerts were attended for each artist?
How many concerts were attended at each venue?
How has the number of concerts attended changed over time?
Are there noticeable trends in concert attendance by year?

Data Cleaning
The following steps were performed to prepare the data for analysis:
Standardized column names (lowercase, trimmed whitespace)
Converted date strings into proper datetime format
Removed rows with invalid or missing dates
Verified there were no missing values in key columns (artist, venue, date)
These steps ensured accurate grouping and time-based analysis.

Analysis & Visualizations
The analysis includes:
Bar charts showing:
Number of concerts attended per artist
Number of concerts attended per venue
Line and bar charts showing:
Number of concerts attended per year
These visualizations make it easy to identify attendance patterns and compare trends over time.

Tools Used
Python
Pandas (data cleaning & aggregation)
Matplotlib (visualization)
Jupyter Notebook
SQL (initial data storage; schema included for reference)

Key Takeaways
Concert attendance varied significantly by artist and venue
Certain years showed higher attendance, indicating periods of increased concert activity
Time-based aggregation was effective in identifying attendance trends
