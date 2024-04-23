# National Parks Capstone Project
- Nashville Software School | Data Analytics - (Cohort DDA12)
---
## Summary
- This project explores how specific characteristics of national parks relate to their engagement, both recreationally and non-recreationally. I collected a vast array of National Park Service (NPS) data from their public portal, and used Python, Excel, Google Slides, and Tableau to clean, analyze, visualize, and present my findings. Additional general information was sourced via web-scraping Wikipedia and downloading climate normals from the National Oceanic and Atmospheric Administration (NOAA) The characteristics I have chosen to dive into are a park's location, area, age, and biodiversity.

## Motivation
- I have always been very interested in natural sciences. That interest is usually directed towards astronomy, but over time I am becoming increasingly interested in nature here on Earth. Many of my favorite memories are connected to spectacular places in national parks. I have flown in a small plane over Denali and landed on a glacier in the mountain range, white-water rafted down many rivers throughout Appalachia, and traversed through Death Valley. There are no better places to feel more alive! National parks are amazing places, and I am gladly taking advantage of the opportunity to combine my passion for them with my professional development as a data analyst.

## Data Question
- How does time, climate, acreage, and biodiversity relate to visitation in national parks?

## Minimim Viable Product (MVP)
- Slides Presentation
    - Analysis of national park's visitation
        - Over time
        - As related to climate
        - As related to biodiversity
        - As related to acreage

## Known Issues and Challenges
- Climate data
    - Many parks did not have a weather station with both temperature and precipitation data; some had no station at all.
        - For these parks, I located the nearest weather station, still easily representative of the local climate, and used that station's data.
        - This data collection had to be done manually, one park at a time, then cleaned and merged.
    - Snow data wasn't collected on many weather stations. Some obviously never get snow, others were missing the sensor.
        - Excluded Snow Data from the analysis
- NPS Data
    - Visitor Use
        - I spent a considerable amount of time unnecessarily manually cleaning excel sheets of data
            - I later realized there was a separate query building tool in the data portal that I used to create the exact CSV files I needed
    - Entrance Fees
        - This data was not readily downloadable or web-scrapable without spending a full day on it, so I manually entered the information; It wasn't much.
            - Unfortunately this information did not yield any interesting findings, and was ultimately excluded for time.
    - Species Data
        - Certain parks lacked any species data, and were excluded from biodiversity-related analysis.

## Data Sources
- **National Park Service** (Data Portals)
    - [NPS Species Data](https://irma.nps.gov/NPSpecies/)
    - [NPS Visitor Use Data](https://irma.nps.gov/Stats/)
    - [NPS Spatial Data](https://public-nps.opendata.arcgis.com/datasets/nps-boundary-1/explore?filters=eyJVTklUX1RZUEUiOlsiTmF0aW9uYWwgUGFyayJdfQ%3D%3D&location=38.968895%2C-99.349395%2C5.89)
    - [NPS Entrance Fees](https://www.nps.gov/aboutus/entrance-fee-prices.htm?park=&state=&entrancePassRequired=&timedEntry=&page=1&parking=)
    - [NPS Acreage Reports (12-31-2023)](https://www.nps.gov/subjects/lwcf/acreagereports.htm)
- **National Oceanic and Atmospheric Administration** (Data Portal)
    - [U.S. Climate Normals (1991-2020)](https://www.ncei.noaa.gov/access/us-climate-normals/)
- **Wikipedia** (Web-scrape)
    - [List of national parks of the United States](https://en.wikipedia.org/wiki/List_of_national_parks_of_the_United_States)
