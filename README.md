# Music Lyrics Exploratory Data Analysis (EDA) 🎵

## Project Overview
Exploratory Data Analysis of a massive **2.3GB dataset** containing music lyrics and timestamps. The goal of this project is to migrate raw CSV data into a relational database and extract insights regarding song structures, vocal density, and trends.

## Tech Stack
- Database: PostgreSQL (handled via DBeaver)
- Language: SQL
- Techniques: Batch Inserts, Data Aggregation, Filtering

## Current Progress
1. Data Migration: Successfully migrated 470,000 rows of raw CSV data into PostgreSQL. Handled memory optimization using batch inserts (10,000 rows per commit).
2. Initial EDA: 
- Counted unique tracks in the sample.
- Analyzed "Vocal Density" by calculating the length of lyrics per track.
- Investigated the "TikTok Effect" by identifying tracks with the fastest vocal start times (minimum `startTimeMs`).

## Files in this Repo
 `1_initial_eda.sql` - SQL queries for the first stage of data exploration.
