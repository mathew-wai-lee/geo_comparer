# geo_comparer

Feature List
* day-to-day Weather
* Demographics (Totals)
* Income or measures of affluence/poverty (median household income vs. national)
* Compare county to county
* Age pyramid
* New Development (housing units) 
* Housing Prices or Housing value
* How Demographics change year by year
* Optional: Schools
* New Industry/Tech breakdown
* Employment Rates
* Private company breakdown
* Education (bachelors and above)
* Residential mobility (are people moving here? Away from here?)
* Public transportation/walkability score
* Affordability index or rent prices

TODO:
* Convert to DBT to build intermediary Tables
* Layer in interactive comparison mapping
* Refactor away from ipynb?
* Add Dagster (optional or a nice to have)
* Refactor dependency management (poetry)
* launch in a website/React app
* Add in Dev bool flags throughout for testing/prod

Notes
* Longest part is api call to fips for weather

Other ideas here: https://data.census.gov/