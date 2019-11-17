# Transit_System

# ETL Transit Systems of the World

# Extract

Two CSV file from Kaggle.com containing data on transit systems throughout the world.<br>
Imported them with Python Pandas in Jupyter Notebook.

# Transform

Converted csv files to dataframes and excluded certain columns.<br>
Renamed remaining columns.<br>
Final columns for cities dataframe: city_id, city_name, start_year, and country.<br>
Final columns for stations dataframe: station_id, station_name, buildstart, opening, and city_id.<br>
Shared column is City_id.<br>
Cities dataframe had no nulls.<br>
Dropped null values from stations dataframe.<br>
Counted number of dropped rows = 10% of station data so kept nulls to have them accounted for after ETL process.<br>

