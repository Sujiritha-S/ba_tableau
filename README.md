# British Airways Review Dashboard

## Project Overview
This interactive Tableau dashboard visualizes passenger reviews of British Airways, focusing on various in-flight experience categories. It enables quick insights into review patterns by aircraft, seat type, traveler demographics, and geography and to explore and present **average customer review scores** across multiple service categories and breakdowns, helping identify what aspects of British Airways’ service stand out or need improvement.

## Dashboard Preview
<img width="1580" height="984" alt="dashboard-preview" src="https://github.com/user-attachments/assets/dd95d824-15af-4b33-95c8-b239d8fd4fe2" />

## Files Included
- ba_reviews.csv - Primary dataset for analysis
- Countries.csv - Mapping file for geographicala visual
- BA_Dashboard.twbx - Tableau packaged workbook
- dashboard-privew.png - Dashboard Screenshot

## Features / Highlights
- KPI Summary: Total Reviews, and Average Ratings for Value for Money, Seat Comfort, Ground Service, Food & Beverages, Entertainment, and Cabin Staff Service  
- Bar Chart: Average Overall Rating & Seat Comfort by Seat Type  
- Butterfly Chart: Average Overall Rating and Number of Reviews by Aircraft  
- Geo Map: Average Overall Rating by Country (gradient color scale)  
- Stacked Bar Chart: Average Ratings by Traveler Type across all service categories  
- Line Chart: Average Overall Rating trend over time (monthly)  
- Interactive Filters: Trip Verified, Traveler Type, Seat Type, Country — with all visuals updating dynamically

## Tools & Technologies Used
- Tableau Public Desktop Edition Version 2.0
- Data source: Publicly available dataset
  
## Calculations / Logic
- Averages for each review category (e.g., Food & Beverages, Ground Service)
- Count of Reviews per aircraft, traveler type, and seat type
- Butterfly charts built using dual-axis method

## Key Insights / Observations
- Premium economy and First Class travelers report higher satisfaction with Seat Comfort.
- Certain aircraft types consistently score lower in Overall Ratings.
- Traveler type significantly influences perceptions of Ground Service and Food quality.
- Not all countries follow the same satisfaction trends — some regions are outliers with either high or low scores.
- Ratings dipped slightly during specific months, potentially indicating service inconsistency or external factors.

## Future Enhancements
- Add comparison with competing airlines
- Include sentiment analysis from text reviews (if available)
- Integrate seasonal or flight-duration filters
- Add star rating conversion logic for categorical visual representation

## Notes
- Most metrics displayed are **averages** — noted clearly using `*` and legend text in the dashboard.
- This project is built using publicly available data and serves as part of a personal portfolio focused on Tableau-based visual storytelling.

