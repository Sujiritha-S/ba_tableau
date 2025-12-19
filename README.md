# British Airways Review Dashboard

An interactive Tableau dashboard analyzing British Airways passenger review ratings across service categories, aircraft types, traveler segments, and geography.

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

## Future Enhancements
- Add comparison with competing airlines
- Include sentiment analysis from text reviews (if available)
- Integrate seasonal or flight-duration filters
- Add star rating conversion logic for categorical visual representation

## Notes
Most metrics displayed are **averages** — noted clearly using `*` and legend text in the dashboard.

