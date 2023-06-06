# home-sales
The focus of the project is to use SoarkSQL to determine key metrics about home sales data.  The project uses Spark to create temporary views, to partition the data cache and then to uncache a tempoary table.

# Questions to analyze
The project looked to return metrics related to
- The average price for a four-bedroom house sold for each year? Answer rounded to two decimal places.
- The average price of a home for each year of homes built.  Only interested in 3BA/3BR homes
- The average price of a home for each year of homes built.  Only interested in 3BA/3BR homes with 2,000+ sq feet and 2 floors
- The view" rating for homes costing more than or equal to $350,000

The project also looked to query against cached and uncached data in addition to parquet data
