# XpologUiTask

In this task you will be asked to implement an app using Angular that will fetch data from a remote end point.\
The users of the app will be able to filter the events by time and view the data either as a line chart or a column chart.

Highcharts Documentation: https://api.highcharts.com/highcharts \
API Documentation https://earthquake.usgs.gov/fdsnws/event/1/

Highcharts package already installed. \
No need to install additional packages.

## Implement the following:

1.
    1. Get 10 events from https://earthquake.usgs.gov/fdsnws/event/1/ in geojson format using request params.
    2. Create a simple Line chart & Column chart using Highcharts lib based on earthquake events magnitude prop (path to prop features->properties->mag).
   3. Add a form for propagating start time and end time (YYYY-MM-DD) to events request based on the documentation of the 'Query' method for getting data in appropriate range and updating chart view. 
   4. Add some styling for the form. 
   5. Add reset button.

2. 
    1. Add routing and navigation in header. 
   2. Set 'line' as home page. 
   3. Set '.../line' for page with Line chart  
   4. Set '.../column' for page with Column chart 

3. 
   1. Create a simple Column chart on a separate route based on 5 events from earthquake API.
   2. Add field to filter data by max magnitude value on button click by existed events.
   3. Add reset button.

4. 
   1. Create a popup as a dynamic component (Dynamic component loader) which will open by click on column chart.
   2. Take the first event from the existing array of events and render a short description about the event inside a popup:
       - title (use url property for adding link)
       - type
       - mag (magnitude)
       - time
	
