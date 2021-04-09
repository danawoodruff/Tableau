https://public.tableau.com/views/NYCBikeStations/Dashboard?:language=en&:display_count=y&publish=yes&:origin=viz_share_link

<html>
<p align="center"><img width="100%" height="60px" src="static/Images/header.PNG"></p>            
<body>
<p>
<h2>NYC Public Bicycle System Dashboard - with user interactivity</h2>
The project provides a visualization of          utilizing       Mapbox, and deployed utilizing Flask and <a href="https://apple-crisp-42918.herokuapp.com/">Heroku.</a><br>

<h3>Data</h3>
Data was sourced from the Houston Association of REALTORS® and downloaded as a .csv.<a href="https://www.HAR.com"> Visit HAR.</a>


After the visualization was built the data source was routed to the SQL database via [Jupyter Notebook.](static/ETL/Master-github.ipynb).  Python code was added to a [datalayer file.](datalayer.py) to convert to GeoJson, and a route created for the converted data in an [app.py file](app.py). This route is used by two visualizations.  
<p align="center"><kbd><img width="500" height="auto" style= "border:3px solid black;" src="static/Images/geopy_code.PNG"></kbd>
  

  

<p align="center"><kbd><img width="600" height="auto" src="static/Images/landingpage.PNG"></kbd>

<h3>Interactive Map Visualization</h3><br>
The language Python 
<p align="center"><kbd><img width="500" height="auto" src="static/Images/layers.PNG"></kbd>
  


<p align="center"><kbd><img "width="360" height="auto" hspace="25" src="static/Images/popup.PNG"></kbd>&nbsp;&nbsp;<kbd><img width="124" height="auto" hspace="25" src="static/Images/icons.PNG"></kbd></p>


<p align="center"><kbd><img width="600" height="auto" src="static/Images/map.PNG"></kbd>


Users may view code at the following links:

To view the Jupyter Notebook's code: [Python Code](/Data_Cleaning.ipynb)   
To view the data .csvs: [.csvs](/Resources)                       


</body>
</html>
