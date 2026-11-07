# Spotify Listening History Analysis | Power BI

An interactive **Power BI Business Intelligence project** focused on analysing personal Spotify listening history and discovering music consumption patterns over time.

The project explores different aspects of listening behaviour, including album performance, artist activity, track analysis, listening platforms, shuffle usage, skipped tracks and weekday versus weekend listening patterns.

The objective is to transform raw listening history into meaningful insights through interactive visualisations and DAX calculations.

## 🎯 Project Objectives

- Analyse listening trends across different years.
- Identify the most frequently played artists, albums and tracks.
- Compare music listening patterns on weekdays and weekends.
- Explore listening behaviour across different platforms.
- Analyse skipped tracks, shuffle usage and playback patterns.
- Evaluate year-over-year changes in music listening activity.

## 📂 Dataset Overview

- **Dataset:** Spotify Listening History.
- **File Name:** `spotify_history.csv`.
- **Dataset Type:** Personal music streaming history.
- **Total Records:** 149,860.
- **Total Columns:** 11.
- **Date Range:** July 2013 – December 2024.
- **Platforms:** 6.

### Dataset Columns

| Column | Description |
|---|---|
| `spotify_track_uri` | Unique Spotify track identifier |
| `ts` | Date and time of playback |
| `platform` | Platform used for listening |
| `ms_played` | Duration played in milliseconds |
| `track_name` | Name of the track |
| `artist_name` | Name of the artist |
| `album_name` | Name of the album |
| `reason_start` | Reason playback started |
| `reason_end` | Reason playback ended |
| `shuffle` | Indicates whether shuffle was enabled |
| `skipped` | Indicates whether the track was skipped |

### Listening Platforms

- Android
- iOS
- Web Player
- Windows
- Mac
- Cast to Device

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modelling and interactive dashboard development.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Measures, calculations and KPI development.
- **CSV** – Source dataset.

## 🔄 Data Cleaning & Transformation

- Imported the Spotify listening history CSV file into Power BI.
- Reviewed column names, data types and table structures.
- Converted the timestamp column into a proper date/time format.
- Prepared year-based fields for time-series analysis.
- Examined missing values in playback reason columns.
- Verified track, artist and album information.
- Prepared weekday and weekend classifications.
- Organised the data for interactive filtering and reporting.

## 🏗️ Data Modelling

Organised the report using the following tables:

**Main Data Table**

- `spotify_history` – Contains track, artist, album, platform, playback duration and listening behaviour information.

**Supporting Tables**

- `Date_table` – Supports date-based and yearly analysis.
- `calculations` – Supports KPI calculations.
- `album_cal` – Contains album-related calculations.
- `artist_cal` – Contains artist-related calculations.
- `tracks` – Contains track-related calculations.

## 📊 Key DAX Measures & Calculations

- Total Albums
- Total Artists
- Total Tracks
- Latest Year Albums
- Latest Year Artists
- Latest Year Tracks
- Maximum Year
- Year-over-Year Album KPI
- Year-over-Year Artist KPI
- Year-over-Year Track KPI

Advanced DAX functions used:

`CALCULATE()` · `COUNT()` · `COUNTROWS()` · `FILTER()` · `ALL()` · `DIVIDE()` · `SELECTEDVALUE()` · `MAX()` · `MIN()`

## 📈 Power BI Report Pages

### 1. Album Analysis

- Total album count.
- Yearly album trends.
- Latest year album statistics.
- Year-over-year album growth analysis.
- Weekday versus weekend comparison.
- Album ranking and comparison.

### 2. Artist Analysis

- Total artist count.
- Yearly artist trends.
- Latest year artist statistics.
- Year-over-year artist growth analysis.
- Weekday versus weekend comparison.
- Artist ranking and comparison.

### 3. Track Analysis

- Total track count.
- Yearly track trends.
- Latest year track statistics.
- Year-over-year track growth analysis.
- Weekday versus weekend comparison.
- Track ranking and comparison.

## 💡 Key Business Insights

- Yearly analysis provides visibility into changes in music listening activity over time.
- Artist and album comparisons help identify frequently appearing names in the listening history.
- Weekday and weekend comparisons reveal differences in listening patterns.
- Platform analysis provides insights into music consumption across different devices.
- Skipped-track and shuffle information offers additional visibility into listening behaviour.
- Year-over-year comparisons help identify changes in album, artist and track activity.

*Note: Insights are based on the available Spotify listening history records and report filters.*

## 🎛️ Power BI Features

- Interactive KPI cards.
- Year-based trend analysis.
- Area charts for yearly comparisons.
- Donut charts for weekday and weekend analysis.
- Bar charts for album, artist and track rankings.
- Dynamic year-over-year KPI calculations.
- Platform slicer for interactive filtering.
- Minimum and maximum trend indicators.

## 📁 Project Files

- `PowerBI/` – Interactive Power BI report (`.pbix`).
- `Dataset/` – Spotify listening history dataset (`.csv`).

## 👨‍💻 Author

**Devaprakash**

B.Tech Graduate in Artificial Intelligence and Data Science

Aspiring Data Analyst | Power BI | SQL | Python | Excel# Spotify-Analysis-Dashboard
