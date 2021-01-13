# XpologUiTask

Highcharts Documentation: https://api.highcharts.com/highcharts \
API Documentation https://earthquake.usgs.gov/fdsnws/event/1/

Highcharts package already installed. \
No need to install additional packages.

## Points to do

1.1 Get 10 event from https://earthquake.usgs.gov/fdsnws/event/1/ in geojson format using request params.\
1.2 Create a simple Line chart using Highcharts lib based on earthquake events magnitude (path to prop features->properties->mag).\
1.3 Add a form for passing start time and end time (YYYY-MM-DD) to events request based on Documentation 'Query' method for getting data in appropriate range and updating chart view.
Add some styling for the form.
Also add reset button.

2.1 Add routing and navigation in header.
    Set 'line' as home page. \
    &nbsp;&nbsp;&nbsp;&nbsp;'.../line' for page with Line chart  \
    &nbsp;&nbsp;&nbsp;&nbsp;'.../column' for page with Column chart \
2.2 Create a simple Column chart on a separate route based on 5 events from earthquake API.\
2.3 Add field to filter data by max magnitude value on button click by existed events.
Also add reset button.

3.1 Create a popup as a dynamic component (Dynamic component loader) which will open by click on column chart.\
3.2 Take a first event from existed array of events and render short information about event inside popup:\
    &nbsp;&nbsp;&nbsp;&nbsp; - title (use url property for adding link)\
	&nbsp;&nbsp;&nbsp;&nbsp; - type\
	&nbsp;&nbsp;&nbsp;&nbsp; - mag (magnitude)\
	&nbsp;&nbsp;&nbsp;&nbsp; - time
	
