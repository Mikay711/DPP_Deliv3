# Deliverable 3: Data Processing and Rescaling

This repository contains code and processed data for Deliverable 3, focusing on cleaning and rescaling two datasets:
- **Spotify Most Streamed Songs**
- **Billboard Hot 100 Songs (2023)**

## Structure
- `data_processing.Rmd`: RMarkdown file for processing and rescaling the datasets.
- `Processed Data/`: Folder containing:
  - `Spotify_Rescaled.csv`
  - `Hot100_Rescaled.csv`

## Summary of Processing
1. **Spotify Data**:
   - Rescaled percentage-based attributes to 0–1.
   - Categorized `streams` into "low," "medium," and "high."

2. **Hot 100 Data**:
   - Cleaned `Weeks in Charts` and categorized `Rank` into "Top 10," "Top 50," and "Top 100."
   - Grouped `Weeks in Charts` into ranges like "1-10," "11-20," etc.

## How to Use
- View the processing steps in `data_processing.html`.
- Access processed data in the `Processed Data/` folder.

