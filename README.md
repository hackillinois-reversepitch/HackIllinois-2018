# HackIllinois-2018
US Ignite Smart Gigabit Community (SGC) Reverse Pitch Challenge

## Hacking Socio-technical issues with Open municipal data
Welcome to the Reverse Pitch Challenge! We are seeking ideas, business plans, design drafts, or prototypes with gigabit features to support city services! 
Winning projects will receive prizes, opportunities to work with faculty-led research teams and Midwest Big Data Hub mentors after the hackathon, and a chance to showcase your work to the national Smart Gigabit Communities.

## Why Gigabit?
###	Smart communities will require applications that use a lot of bandwidth, such as
-	Interactive, high-definition gaming
-	Augmented Reality for education and training
###	Significant reduction in latency (response times across the system), imagine 
-	Knowing when a flash flood will hit your neighborhood
-	Improved food delivery services with driverless cars
###	Software-defined services that require customization, including
-	Data transmission on a private, secure network
-	Optimizing network resources in real-time, dynamically

*Hint: Check [this file](Gigabit Application Maker.pdf) for some gigabit application ideas*

## What are the Challenges?

### 1. Improved efficiency of City services with data visualization and analysis

The City of Champaign has provided multiple years of Public Works data, geospatial data, and service request data collected via the See.Click.Fix app.

We are seeking gigabit application ideas that can

- Support an interactive data analysis tool in real-time
- Visualize data to identify potential "hotspots" and support decision-making and neighborhood planning
- Easily integrate with GIS or online map (e.g. Google Maps)
- Streamline workflows for the City to support environmental improvements

*Hint: What are the common issues? Are there patterns? How to help users quickly identify and respond to the problems when they are working in the field?*

#### Data

You can download the open municipal public works data from the [data folder](data/) (data will be available on the day of HackIllinois). In the data folder you will find:
- A CSV file contains more than 30K public works log (all_cityworks_records.csv:)
- Shapefiles and Metadata extracted from [this geodabase file](https://goo.gl/wcqWcc)
*The coordinate system we use in these files is NAD 1983 StatePlane Illinois East FIPS 1201 Feet*

### 2. Enhanced monitoring of micro climate change in our City

The City of Champaign needs an improved micro climate monitoring application to help improve weather prediction and observation. The application will create the ability for municipal staff, including police and other emergency agencies, to pro-actively position resources in response to weather events moving across the community.

We are seeking gigabit applications ideas that can

- Develop sensors (hardware) and software to monitor micro climate change
- Easily integrate with GIS or online map (e.g. Google Maps)
- Connect with mobile-app for community members to self report weather activities
- Allow city officials to respond in real-time

*Hint: What data to collect? How to collect, transmit, and visualize these data? How can users quickly identify potential weather threats and take actions?*

## Resources
- See.Click.Fix App: Online app from which the City of Champaign dataset originates (https://seeclickfix.com/)
- Municipal geospatial dataset: GIS data from City of Champaign (https://goo.gl/wcqWcc)
- Illinois Geospatial dataset (https://goo.gl/cDAV1x) 
- Open sourced Weather API (https://openweathermap.org/api)

### GIS Tools
- QGIS (https://qgis.org/en/site). Geocoding is supported by QGIS plugins like MMQGIS described here (https://www.gislounge.com/how-to-geocode-addresses-using-qgis).
- For Python users: Fiona (https://toblerity.org/fiona/manual.html) and GeoPandas (http://geopandas.org), also check this (https://pythongisresources.wordpress.com/category/packages)
- For R users: https://cran.r-project.org/web/views/Spatial.html




