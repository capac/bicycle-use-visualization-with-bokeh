## Data visualization for average weekday public bicycle traffic in London UK

I've dedicated some time to build an interactive scatter plot with [Bokeh](https://docs.bokeh.org/en/latest/) to show average weekday bicycle traffic in London UK. The interactive plot shows the total traffic flux at bicycle stations in downtown London, with the size displaying the sum of the inflow and outflow traffic from each station and the color showing the net flux of the infow and outflow traffic. The blue shifted colors represent a net outflow of bicycles while the shift towards red represents a net inflow of bicycles.

The data displays the total and net fluxes for 935 docking stations, in increments of fifteen minutes, over the course of an average weekday in London. One can notice the outflow of bicycles from the main train station at the Kings' Cross and Waterloo train stations during the morning rush hours around 8 am and the corresponding inflow to the same train stations during the evening rush hours around 6 pm. To the outflow from the train stations corresponds an inflow to the various docking stations in central London. You can also notice an increase in bicycle traffic at the docking stations in Hyde Park and Queen Elizabeth Olympic Park during the afternoon hours.

The data is freely available and can be downloaded from [the public open data web site for TfL](https://cycling.data.tfl.gov.uk/). The CSV file I've used is located in the data folder.

[Data visualization for average weekday public bicycle traffic in London UK using Bokeh - Link to online Bokeh plot on Heroku](https://bicycle-use-with-bokeh.herokuapp.com/main)
