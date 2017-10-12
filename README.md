# WSJ_CollegeRankings2018

Repository with files used for visualizing different aspects of the [THE / Wall Street Journal's 2018 College Rankings Report](https://www.timeshighereducation.com/rankings/united-states/2017#!/page/0/length/25/sort_by/rank/sort_order/asc/cols/stats).  You can view the published report on [Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiYWM3MmYzODktNmMwNi00NjQ3LWFlY2QtY2I3MWMxN2JiY2NkIiwidCI6ImJhNWE3ZjM5LWUzYmUtNGFiMy1iNDUwLTY3ZmE4MGZhZWNhZCIsImMiOjN9).

### Files Available
- wsj_data.csv: Data pulled from the newspaper versions of the 2018 College Rankings Report. Used OCR technology to reconstruct the table. Also contains a "loc_string" used to query ARCGis Maps and/or Google Maps API.
- wsj_locs.csv: Geocoding information pulled from Google Maps. For plotting locations.
- census_data.csv: Regional and state data pulled from the US Census Bureau. Raw table is also available.

### Methodology
The overall Wall Street Journal/Times Higher Education College Rankings 2017 methodology explores four key areas. A full description of the methodology is available on [the report's website](https://www.timeshighereducation.com/the-wall-street-journal-times-higher-education-college-rankings-2017-table-information).

#### Resources
Does the college have the capacity to effectively deliver teaching? The Resource area represents 30 per cent of the overall ranking. Within this we look at:

- Finance per student
- Faculty per student
- Research papers per faculty

#### Engagement

Does the college effectively engage with its students? Most of the data in this area is gathered through the THE US Student Survey. The Engagement area represents 20 per cent of the overall ranking. Within this we look at:

- Student engagement
- Student recommendation
- Interaction with teachers and students
- Number of accredited programmes

#### Outcomes

Does the college generate good and appropriate outputs? Does it add value to the students who attend? The Outcomes area represents 40 per cent of the overall ranking. Within this we look at:

- Graduation rate
- Value added to graduate salary
- Academic reputation

#### Environment

Is the college providing a learning environment for all students? Does it make efforts to attract a diverse student body and faculty? The Environment area represents 10 per cent of the overall ranking. Within this we look at:

- Proportion of international students
- Student diversity
- Staff diversity
- Student inclusion
