# British Airways Review Dashboard

This interactive Tableau dashboard visualizes passenger reviews of British Airways, focusing on various in-flight experience categories. It enables quick insights into review patterns by aircraft, seat type, traveler demographics, and geography.


## Objective

To explore and present **average customer review scores** across multiple service categories and breakdowns, helping identify what aspects of British Airways’ service stand out or need improvement.


## Dataset Overview

- **Source**: 
  - ba_reviews.csv
  - Countries.csv
- **Volume**: Over 1,300 reviews

## Dashboard Features

### KPI Summary
- **Total Reviews**, along with **Average Ratings** for:
  - Value for Money
  - Seat Comfort
  - Ground Service
  - Food & Beverages
  - Entertainment
  - Cabin Staff Service  
- Asterisk (`*`) denotes metrics displayed as **averages**.

### Visuals Used 

| Chart | Description |
|-------|-------------|
| **Bar Chart** | Avg. Overall Rating & Seat Comfort by Seat Type |
| **Butterfly Chart** | Avg. Overall Rating and No. of Reviews by Aircraft |
| **Map** | Avg. Overall Rating by Country (gradient colored) |
| **Stacked Bar Chart** | Avg. Ratings by Traveler Type across categories |
| **Line Chart** | Avg. Overall Rating trend by Month |


## Interactivity

- Filters by:
  - `Trip Verified`
  - `Traveller Type`
  - `Seat Type`
  - `Place (Country)`
- All visuals dynamically adjust based on filter selections.


## Tools Used

- **Tableau Public** – Used to build and design the entire dashboard using publicly available review, countries data.


## Notes

- Most metrics are **averaged** across reviews. These are clearly indicated with an asterisk and described in footnotes.
- Color schemes and visual layout have been designed to ensure **clarity and comparability** across segments.


## Author

- Created by Sujiritha as part of a Tableau practice project.  
- Feel free to explore, reuse, or provide feedback!
- This is my **first Tableau dashboard**, built to explore real-world data and gain hands-on experience in data visualization.


