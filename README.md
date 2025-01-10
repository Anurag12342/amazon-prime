# Amazon Prime Video Dashboard

## Project Overview

This project presents an in-depth Power BI dashboard that analyzes Amazon Prime Video's content. The dashboard provides insights into total titles, average ratings, genre distribution, director counts, content distribution by country, and more.

## Table of Contents

1. [Data Collection and Preparation](#data-collection-and-preparation)
2. [Setting Up Power BI](#setting-up-power-bi)
3. [Creating Visualizations](#creating-visualizations)
   - [Total Titles and Ratings](#total-titles-and-ratings)
   - [Total Genres and Directors](#total-genres-and-directors)
   - [Content Timeline](#content-timeline)
   - [Ratings Distribution](#ratings-distribution)
   - [Genres Distribution](#genres-distribution)
   - [Content by Country](#content-by-country)
   - [Movies vs TV Shows](#movies-vs-tv-shows)
   - [Release Year Trends](#release-year-trends)
4. [Adding Filters](#adding-filters)
5. [Formatting and Design](#formatting-and-design)
6. [Publishing the Dashboard](#publishing-the-dashboard)
7. [Setup Instructions](#setup-instructions)
8. [Contributing](#contributing)
9. [License](#license)

## Data Collection and Preparation

1. **Data Sources**: Collected data from Amazon Prime Video's content listings, including title, rating, genre, director, release year, and country of origin.
2. **Data Cleaning**: Used Python to clean and preprocess the data. This involved handling missing values, standardizing genres, and categorizing ratings.
3. **Data Export**: Saved the cleaned data in CSV format for easy integration with Power BI.

## Setting Up Power BI

1. **Installation**: Installed Power BI Desktop from the official Microsoft website.
2. **Data Loading**: Opened Power BI Desktop and loaded the cleaned data file (CSV) into the application.

## Creating Visualizations

### Total Titles and Ratings

1. **Card Visualization**: Used to display the total number of titles (9,655) and the total ratings (25). Configured the data fields to show the appropriate measures.

### Total Genres and Directors

1. **Card Visualization**: Used to display the total number of genres (519) and the total number of directors (5,771). Configured the data fields to represent these counts.

### Content Timeline

1. **Line Chart**: Displayed the span of content from 1920 to 2021. Configured the axis to show the timeline and data points for each year.

### Ratings Distribution

1. **Bar Chart**: Showed the distribution of ratings across different categories. Configured the data fields to display the count of titles for each rating:
   - 13+: 2.1K
   - 16+: 1.5K
   - ALL: 1.3K
   - 18+: 1.2K
   - R: 1.0K
   - PG-13: 0.4K

### Genres Distribution

1. **Bar Chart**: Showed the number of shows in various genres. Configured the data fields to display the count of titles for each genre:
   - Drama: 986
   - Comedy: 536
   - Drama, Suspense: 399
   - Comedy, Drama: 377
   - Animation, Kids: 356
   - Documentary: 350

### Content by Country

1. **Map Visualization**: Displayed the distribution of shows by country. Configured the data fields to highlight the number of titles in each country, with North America prominently highlighted.

### Movies vs TV Shows

1. **Pie Chart**: Illustrated the proportion of movies and TV shows. Configured the data fields to show the percentage distribution:
   - Movies: 1.85K (19.18%)
   - TV Shows: 7.81K (80.82%)

### Release Year Trends

1. **Line Chart**: Showed the number of shows released each year. Configured the data fields to display the release year and the count of titles, highlighting trends over time.

## Adding Filters

1. **Slicers**: Added slicers for ratings, genres, and release years to allow dynamic filtering of the data.
2. **Configuration**: Ensured the slicers interact with all visualizations for a cohesive experience.

## Formatting and Design

1. **Custom Theme**: Applied a custom theme to match the branding of Amazon Prime Video.
2. **Titles and Labels**: Added descriptive titles, labels, and tooltips for better readability and user experience.
3. **Layout Optimization**: Ensured the dashboard is visually appealing and easy to navigate.

## Publishing the Dashboard

1. **Save File**: Saved the Power BI file (.pbix) after completing all visualizations and formatting.
2. **Publish**: Published the dashboard to the Power BI service for sharing with stakeholders and for collaborative work.

## Setup Instructions

1. Clone this repository to your local machine.
2. Open the Power BI file (`Amazon_Prime_Video_Dashboard.pbix`) using Power BI Desktop.
3. Ensure the data files (CSV) are placed in the correct path.
4. Refresh the data in Power BI to load the latest information.
5. Explore the dashboard and interact with the visualizations and filters.


