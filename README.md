# distance-mapping
A Python colab notebook to read a CSV, convert postal code to coordinates, and visualize on a map with dot size proportional to the count of points it represents

The CSV is expected to be a linked Google Drive and have the following structure: 
postal_code |	country_code	| city |	state

References:
- Country codes: https://pgeocode.readthedocs.io/en/latest/
- USA shapefile: https://www.census.gov
- World shapefile: https://www.naturalearthdata.com/
