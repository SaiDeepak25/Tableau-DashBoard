# British Airways Customer Experience Analysis Dashboard
This project involves creating an interactive Tableau dashboard to analyze customer reviews for British Airways.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contributing](#contributing)


## Overview
The dashboard visualizes customer experience metrics across various demographics, traveler types, and seat classes, helping to identify trends in satisfaction levels.

## Features
- Interactive Filters: Traveler Type, Seat Type, Date Range, Continent
- Key Metrics: Overall Rating, Cabin Staff Service, Entertainment, Ground Service, Seat Comfort, Food and Beverages, Value for Money
- Visualizations: Time Series, Geographic Map, Aircraft Type Breakdown

## Installation and Setup

1. Load the Data in Tableau
 Open Tableau Desktop.
 Navigate to "File" > "Open" and connect to the cleaned dataset (e.g., `ba_reviews.csv`).
 Ensure fields like `Traveler Type`, `Seat Type`, `Date`, and `Continent` are correctly recognized as dimensions.

2. Create Calculated Fields
 Create fields for `Average Ratings` if not already in the dataset.
 For example, you can calculate the average for metrics like Cabin Staff Service with:
   - AVG([Cabin Staff Service])

 3. Build Visualizations
 - Time Series: Create a line chart for trends in average ratings over time.
 - Map: Use a geographic map to show average food rating by country.
 - Bar Chart: Display a breakdown of average food rating by aircraft type.

 4. Design the Dashboard
 Open a new Dashboard in Tableau.
 Drag each sheet (Time Series, Map, Bar Chart) onto the dashboard canvas.
 Add filters to the dashboard for Traveler Type, Seat Type, Date Range, and Continent to enable interactivity.
 Adjust layout, titles, and tooltips for improved readability.

 ## Usage

 Interacting with the Dashboard
 - Filters: Select specific values for Traveler Type, Seat Type, Date Range, and Continent to refine your analysis.
 - Analyzing Visuals:
   - Observe trends over time with the Time Series visualization.
   - Explore geographic trends on the map.
   - Check aircraft-specific ratings with the bar chart.

 Example Workflow:
  Step 1: Choose Business as Traveler Type and Economy Class as Seat Type.
  Step 2: Set Date Range to the last 12 months.
  Step 3: Focus on Europe in the Continent filter.
 Step 4: Analyze resulting trends in average ratings across metrics.

 ## Contributing
 Contributions are welcome! Fork the repository, make improvements, and submit a pull request.
