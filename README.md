# Spotify Global Chart Performance Dashboard (Power BI)

## Overview
An interactive Power BI dashboard that explores what drives streams and chart performance for songs on Spotify's global charts, including chart longevity, peak position, and lyric length.

## Dataset
[Spotify Global Chart Totals & Lyrics](https://www.kaggle.com/datasets/batudev/spotify-global-chart-totals-and-lyrics) from Kaggle. 8,000+ songs with chart stats, streams, and lyrics. Covers every track that appeared on Spotify's Global Weekly Chart between September 29, 2013 and July 23, 2026.

## Tools
Power BI Desktop, Power Query

## Dashboard Preview
<img width="1432" height="801" alt="spotify chart performance dashboard ss" src="https://github.com/user-attachments/assets/7d1dbf50-d64f-42f8-b8b5-e69f123eb96b" />


## What I Did
- Cleaned and transformed the data in Power Query: renamed fields, handled null values, corrected data types, and removed unused columns
- Created calculated columns for lyric word count, lyric length group, chart position group, and #1 status to enable deeper segmentation
- Built an interactive multi-visual dashboard with bar, column, and scatter charts analysing streams, chart longevity, peak position, and lyric length
- Identified top songs and artists by total streams and analysed the relationship between weeks on chart and total streams



## Questions Explored
- Which songs and artists have the most total streams?
- Is there a relationship between weeks on chart and total streams?
- How many songs reach #1, and how many peak outside the Top 10?
- Does lyric length relate to chart performance?

## Files
- IS DISPLAYED IN ISSUES 
