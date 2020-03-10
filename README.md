# Map flight tracking

Visualize flight tracks on a map with Python framework (geo/moving/pandas, contextily...)

Flight data are stored as [pandas](https://pandas.pydata.org/) / [GeoPandas](http://geopandas.org/) dataframes

Trajectory is built with [movingpandas](https://pypi.org/project/movingpandas/) and interpolation and projection are realized with movingpandas functions

The map background is built with [contextily](https://github.com/darribas/contextily)

The final animated gif is built with PIL and matplotlib



Example: one flight from Marrakesh to Rome

![flight](marrakesh-rome.gif)



## Running the tests

Run the demo-flight-tracking notebook to see how to build the Marrakesh-Rome example

## Built With

* [pandas](https://pandas.pydata.org/) - Python Data Analysis Library

* [GeoPandas](http://geopandas.org/) - GeoPandas is an open source project which extends the datatypes used by pandas to allow spatial operations on geometric types. 

* [movingpandas](https://pypi.org/project/movingpandas/) - Implementation of Trajectory classes and functions built on top of GeoPandas

* [contextily](https://github.com/darribas/contextily) - Context geo-tiles in Python


## Authors

* **Thomas Dubot** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

Thanks to [Anita Graser](https://github.com/anitagraser/movingpandas) for her tutorials and videos on movingpandas