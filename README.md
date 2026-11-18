# database_integration
1. Loads the CityBikes data and the Census data into pandas DataFrames
2. Cleans the bike data (removes Lime networks with no dock counts, combines networks in the same city)
3. Adds full state names and fixes a few city names so the two datasets match
4. Merges the datasets using `city` and `state`
5. Checks the merged data for duplicates, missing values, and data types
6. Saves everything to a SQLite database called `bike_share.db`
