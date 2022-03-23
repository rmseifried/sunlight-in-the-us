# Sunlight in the U.S.

This web map shows what time the sun set on December 21, 2021 in the 1,000 largest cities in the U.S.

## Why it exists

The web map was created for the workshop [Build a Web Map (with open-source software)](https://umass-gis.github.io/workshops/content/web-map/) offered through UMass Amherst Libraries in March 2022. I was looking for a timely dataset to use in a demonstration and, since Daylight Savings Time is (at the time of this writing) up for debate in Congress, I figured, "Why not make a map showing how much darkness Standard Time forces us to endure each winter?" Hence this map.

## Where the data came from

City point locations are courtesy the [SimpleMaps US Cities Database](https://simplemaps.com/data/us-cities). 

Sunrise, sunset, and hours of daylight were retrieved from [Sunrise-Sunset.org](https://sunrise-sunset.org) via their API. The Python script I wrote to query the API and format the data can be found in the [UMass GIS workshop repository](https://github.com/umass-gis/workshops/tree/main/content/web-map/python).

