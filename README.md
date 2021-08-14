# sqlalchemy-challenge
Climate analysis and API

## Background
This Project examines temperature and precipitation data from a weather station located in Hawaii

## Climate Analysis
To analyze climate data SQLalchemy was utilized to be able to reflect the available data. Inspector was utilized to discern the columns, data types and keys. The Precipitation data is plotted against their corresponding dates. We can see that there is consistent levels of precipitation with several instances per year of larger amounts of precipitation. If we examine the temperature data against the frequency of the recorded temperature we get a close to normal data distribution that reveals a relatively moderate climate with the max frequency of temperature recordings ranging from 70-80 degrees

## API
To make the data available to other aspiring researchers a climate APP was developed utilizing python and flask. Routes were created and correspond to temperature observations, precipitation, stations, and custom routes to calculate minimum, average, and max temperature data for dates after or in between specific start/end dates.
