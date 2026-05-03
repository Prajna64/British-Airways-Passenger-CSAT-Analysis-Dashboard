# British-Airways-Passenger-CSAT-Analysis-Dashboard

Project Overview
-----------

This project analyzes British Airways passenger satisfaction using two datasets: customer reviews and a country reference table. The goal is to understand satisfaction patterns across traveller types, seat classes, continents, aircraft types, and recommendation behavior. The final output is an interactive Excel dashboard built with pivot tables, slicers, and charts.

---------------
Dataset Description
-------------

ba_reviews.csv: Contains passenger review data including overall rating, seat type, traveller type, route, aircraft type, recommendation status, and service-related ratings.    

Countries.csv: Contains country, continent, and region information used to map passenger place to continent for geographic analysis.    

-------------
Data Cleaning
--------------

- Imported both CSV files into Excel tables.       
- Converted date fields into proper date format.
- Removed duplicates.
- Kept -1 values as missing/not applicable ratings.
- Created a Month column from flight date.
- Created a Continent column using lookup from the Countries dataset.
------------
Exploratory Data Analysis
--------------

- Average rating by traveller type.
- Average rating by seat type and traveller type.
- Average rating by seat type and recommended status.
- Average rating by continent.
- Average rating by country.
- Top aircraft types by average rating.
- Count of reviews by seat type.
- Overall CSAT KPI analysis.
--------------
Dashboard
-------------

The dashboard includes KPI cards, pivot charts, and interactive slicers for traveller type, seat type, recommended status, and continent. It provides a quick visual summary of passenger satisfaction across multiple dimensions.

------------
Key Findings
--------

- Overall average rating is low.
- Less than half of passengers recommended the airline.
- Dissatisfaction is consistent across traveller types and continents.
- Economy class contributes the highest review volume.
- Aircraft type is not the main driver of satisfaction; service quality is more important.

-----------
Tools Used
---------

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- VLOOKUP
- Data Cleaning and Visualization

------------

Conclusion
--------

This project transforms raw passenger review data into an interactive dashboard that helps identify major CSAT issues and supports data-driven decisions for service improvement.

----
AUTHOR   
Prajna C   
Aspiring Data Analyst
