# National Parks Capstone Project
- Nashville Software School | Data Analytics - (Cohort DDA12)
---
## Summary
- This project explores how specific characteristics of national parks relate to their recreational visitation. I collected a vast array of National Park Service (NPS) data from their IRMA data portal, and used Python, Excel, Google Slides, and Tableau to clean, analyze, visualize, and present my findings. Additional general information was sourced via web-scraping Wikipedia and the National Oceanic and Atmospheric Administration (NOAA) climate normals query tool. This project focuses on time, biodiversity, and climate of the national parks.

## Motivation
- I have always been very interested in natural sciences. That interest is usually directed towards astronomy, but over time I am becoming increasingly interested in nature here on Earth. Many of my favorite memories are connected to spectacular places in national parks. There are no better places to feel more alive! National parks are amazing places, and I am gladly taking advantage of the opportunity to combine my passion for them with my professional development as a data analyst.

## Data Question
- How does time, biodiversity, and climate relate to recreational visitation in national parks?

## Minimim Viable Product (MVP)
- Slides Presentation
    - Analysis of national park's visitation
        - As related to time
        - As related to climate
        - As related to biodiversity

## Known Issues and Challenges
- Climate data
    - Many parks did not have a weather station with both temperature and precipitation data; some had no station at all. For these parks, I located the nearest weather station, still easily representative of the local climate, and used that station's data. This data collection had to be done manually, one park at a time, but I was able to automate the cleaning and merge the data easily.
    - Snow data wasn't collected on many weather stations. Some obviously never get snow, others do but were missing the sensor. Snow data was excluded from the analysis
- NPS Data
    - Visitation
        - I spent a considerable amount of time manually cleaning excel sheets of data unnecessarily, and later realized there was a separate query building tool in the data portal that I used to create the exact CSV files I needed. I learned to focus more time on understanding an unfamiliar database fully before beginning work with it.
    - Entrance Fees
        - This data was not readily downloadable or web-scrapable without spending a full day on it, so I manually entered the information over about 15 minutes. I believe this was the right choice, and prioritized meeting the deadline without overcomplicating things. I am here to learn, but a deadline is a deadline, and the juice wasn’t worth the squeeze.
        - Unfortunately this information did not yield any significant findings, and was ultimately excluded for time.
    - Acreage
        - This data had a some interesting facts, such as Alaska having more than half of all national park land, but ultimately did not lead to significant findings. It was excluded from the presentation for time.
    - Biodiversity
        - A few national parks lacked any species data, and were excluded from biodiversity-related analysis.


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
