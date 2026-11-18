# database_integration
Loads the CityBikes data and the Census data into pandas DataFrames
Cleans the bike data (removes Lime networks with no dock counts, combines networks in the same city)
Adds full state names and fixes a few city names so the two datasets match
Merges the datasets using `city` and `state`
Checks the merged data for duplicates, missing values, and data types
Saves everything to a SQLite database called `bike_share.db`
