## Data visualization for average weekday public bicycle traffic in London UK

![]()

I've dedicated some time to build an interactive scatter plot with [Bokeh](https://docs.bokeh.org/en/latest/) to show average weekday bicycle traffic in London UK. The interactive plot shows the total and net traffic flux for 935 docking stations, in increments of fifteen minutes, with the size displaying the sum of the inflow and outflow traffic from each station and the color showing the net flux of the infow and outflow traffic. The plot can be animated by a play buttom, zoomed in and filter by total traffic flux and tooltip information can also be accessed by cursor hover-over on each docking station, showing the details concerning total traffic, net traffic and docking station name.

The data is freely available and can be downloaded from [the public open data web site for TfL](https://cycling.data.tfl.gov.uk/). The CSV file I've used is located in the data folder. Check out the visualization in the link below.

[Data visualization for average weekday public bicycle traffic in London UK using Bokeh](https://bicycle-use-with-bokeh.herokuapp.com/main)
