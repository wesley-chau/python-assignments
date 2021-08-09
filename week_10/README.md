Flight Tracker FINAL


Tools:

Jupyter Notebook
OpenSky Network - supplies open air traffic data to be converted into a visual flight tracker
REST API - gets airplane data within an area extent using WGS84 coordinates system
Bokeh Library - 
Pandas Library
JSON
NumPy Library


Process:

Retrieve air traffic data using REST API and OpenSky. Airplane data is requested within specific boundaries (WGS84 coordinates system).
Make request query.
Response data fed into Pandas data frame.
Pandas data frame 'head method' utilized to view the first 5 top rows of data.
Using Bokeh library, data is used to locate airplanes on a map.
Convert coordinates - Use wgs84_web_mercator_ function to transform WGS84 coordinate into web Mercator coordinate system.
Specify plotting area for coordinates (ie. basemap).
Plot airplane position.
Add hover state for more airline data.
Run tracker on new browser window on local server.

