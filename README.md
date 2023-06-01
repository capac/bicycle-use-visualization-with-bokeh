## Data visualization for average weekday public bicycle traffic in London UK

<center>

![Image of data visualization for average weekday public bicycle traffic in London UK](https://github.com/capac/bicycle-use-visualization-with-bokeh/raw/master/images/bike_traffic.png)

</center>

I've dedicated some time to build an interactive scatter plot with [Bokeh](https://docs.bokeh.org/en/latest/) to show the average weekday bicycle traffic in London UK for 2019. The interactive plot shows the total and net traffic flux for 935 docking stations and 12940 bicycles, with the size displaying the total traffic flux, given by the sum of the inflow and outflow traffic, and the color showing the net flux of the inflow and outflow traffic from each station. The blue shifted colors represent a net outflow of bicycles while the shift towards red represents a net inflow of bicycles.

The plot can be animated by a play button which displays the activty over a 24 hour period in fifteen minutes increments. It can be zoomed in and filtered by total traffic flux and contains tooltip information which can be accessed by cursor hover-over on each docking station, showing the details concerning total traffic, net traffic and docking station name.

The data is freely available and can be downloaded from [the public open data web site for TfL](https://cycling.data.tfl.gov.uk/). The CSV file I've created is located in the data folder. Check out the visualization at the link below.

[Data visualization for average weekday public bicycle traffic in London UK using Bokeh](https://bicycle-use-with-bokeh.herokuapp.com/main)

UPDATE (2023-03-27): Due to the closure of the free-tier Heroku hosting for the Bokeh web app I had created, the link above doesn’t work anymore. The code however still works locally with Bokeh and the proper dependecnies. You are more than welcome to try running it on your computer.
