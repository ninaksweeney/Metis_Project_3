# The Opportunity Within Amtrak: America's Railroad

## Abstract   

One of Amtrak's short-term goals is to gain more young riders, and for a young population distressed by climate change, it happens to be a great low-carbon alternative to air and car travel. However, ridership and revenue remain historically low for the company, which has been severely harmed by COVID-19. Amtrak is largely dependent on government subsidies and needs a low-risk, low-cost way to appeal to new audience segments. Our hypothesis is that environmentally focused ads targeted at young, climate-conscious air travelers will increase Amtrak's ridership and revenue. 

Tableau visualizations & Presentation (within tableau stories) can be viewed [here](https://public.tableau.com/app/profile/nina7004/viz/AmtrakOpportunities/AllRoutesClimate#1). 

## Design   
Given a tight budget for advertising, we sought a small, super-targeted population with which to pilot Amtrak's climate-focused ad campaign. First, we found the most popular U.S. airline routes under 1000 miles which are also served by Amtrak within 24 hours or less. Then, using U.S. Climate Opinion data, we drilled down to routes where the populations of both destinations are likely to be receptive to climate messaging. Lastly, we found colleges along the routes where at least 5% of the freshman class would be travelling along that route to get to their home state. This led to about 40 schools with young, regular travelers who will need to go home for the holidays - hopefully using Amtrak. 

Project Scoping can be read in the Project3_Scoping.md document within this repository. This process included the development of: 
- A problem statement & impact hypothesis
- Nontechnical & technical scoping
- Current & Future state
- Trade offs & constraints
- Evaluation criteria

## Data  
We used a number of datasets to find our target population. We used [air travel data](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FHK) from the Bureau of Transportation Statistics from 2017-2019, which samples 10% of U.S. flights from those years. [Amtrak routes](https://data-usdot.opendata.arcgis.com/datasets/amtrak-routes/explore?location=33.813562%2C-96.584950%2C4.00&showTable=true) from the Dept of Transportation and [College/University geography data](https://nces.ed.gov/programs/edge/Geographic/SchoolLocations#) from NCES assisted with mapping. [Climate change opinion data](https://climatecommunication.yale.edu/visualizations-data/ycom-us/) was collected from Yale's 2020 study, and [college/university details](https://educationdata.urban.org/data-explorer/colleges/) from the Urban Institute. 

To create our maps, this data was joined on metro area and visualized in Tableau. 

## Algorithms  
The primary Google Sheets functionalities used were pivot tables, charts, conditional formatting, and Vlookup. Once we moved the data into Tableau, we used dual-axis maps to show geographical relationships between datasets. For communication purposes, we used Tableau's worksheet, dashboard, and story views to clearly present the project trajectory. 


## Tools  
We completed this project largely in Google Sheets and Tableau, with some preliminary data cleaning & aggregation completed in Python. We used Google Sheets to visualize route advantages and narrow down the routes, join datasets, and complete initial visualization. We then loaded many iterations of the Google Sheets data into Tableau to gain a better understanding of the geographical relationships between datasets. We executed the final mapping and visualization, as well as the communication of the project, in Tableau. 

## Communication
We completed a 5-minute presentation of our findings, including initial recommendations for a pilot campaign as well as future modeling opportunities. Slides and visuals for this project are included in this repository. Future work may include building a predictive model to better inform the selection of target audiences for climate-focused advertising. 
