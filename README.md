# IGORS LIBERTS
## PROJECTS
### Mapping Residential Real Estate Prices
This project analyses and visualises the average prices of flats and houses across different regions in Latvia for the year 2024. It involves processing real estate transaction data, integrating it with geographic information, and mapping regional price differences. The analysis includes a national overview through choropleth maps as well as a detailed heatmap for a selected municipality, providing insights into spatial trends in residential property prices across the country.

https://github.com/iliberts/projects/tree/main/Mapping%20Residential%20Real%20Estate%20Prices

### School Bus Routes with Real-time Tracking
This web app provides an interactive map designed to help make sense of school bus routes. Unlike public transport networks, school buses are meant to get pupils to and from specific schools, so showing the full network isn’t as useful. Instead, the app focuses on giving clear information about which buses stop where, what time they arrive, and which schools they go to. Individual routes can be selected to see its full path, stops, and direction of travel, making it easy to understand how each bus runs and where it goes. During service hours, the app also provides real-time tracking based on live GPS data from the buses, meaning the map reflects their actual positions rather than estimated movements from the schedule.

Developed in TypeScript using React and React-Leaflet.

https://marsruti-sigulda.vercel.app/

### GEO SIGULDA
Place for interactive web maps of Sigulda Municipality, offering a clearer way to explore and understand location-based information. Data that can be difficult to interpret in a list or spreadsheet becomes much more accessible when visualised on a map. Viewing information in its geographical context makes it easier to spot patterns, relationships, and relevance that might otherwise be overlooked. The maps are built using mobile-friendly React Leaflet, providing a faster and more responsive experience compared to solutions like ArcGIS Online. This approach prioritises speed and usability in web mapping.

https://geo.sigulda.lv/

### Data Cleaning: Roads and Streets
This is a data cleaning project working with hierarchically structured spreadsheets containing information on roads and streets in Sigulda Municipality. The data is spread across four Excel worksheets and includes territorial groupings and sectioned entries. All data is consolidated into a single table, with territorial divisions extracted, branches identified, and unique IDs assigned to each road or street.

https://github.com/iliberts/projects/tree/main/Data%20Cleaning%3A%20Roads%20and%20Streets

### Offset Overlapping Routes
This web app explores a practical solution to a common issue in visualising a route network map: overlapping routes often obscure one another, making it difficult to distinguish individual lines. The app proposes a method to address that by dynamically splitting routes into segments based on where overlaps occur and offsetting only those overlapping segments. This is done 'on the fly', without altering the original route geometries (polylines), improving map readability while keeping the underlying data intact.

Developed in TypeScript using React and React-Leaflet with PolylineOffset.

https://route-offset.vercel.app/
