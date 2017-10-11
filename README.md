# WSJ_CollegeRankings2018
Repository with files used for visualizing different aspects of the Wall Street Journal's 2018 College Rankings Report.  

You can view the published report on [Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiYWM3MmYzODktNmMwNi00NjQ3LWFlY2QtY2I3MWMxN2JiY2NkIiwidCI6ImJhNWE3ZjM5LWUzYmUtNGFiMy1iNDUwLTY3ZmE4MGZhZWNhZCIsImMiOjN9).

Data files are:
- wsj_data.csv: Data pulled from the newspaper versions of the 2018 College Rankings Report. Used OCR technology to reconstruct the table. Also contains a "loc_string" used to query ARCGis Maps and/or Google Maps API.
- wsj_locs.csv: Geocoding information pulled from Google Maps. For plotting locations.
- census_data.csv: Regional and state data pulled from the US Census Bureau. Raw table is also available.
