#architecture 
The Core provides the base on which to build plugins for doing pre-processing. It consists of four major pillars: 

- Managing input and output of data, which is usually handled by a [[DataAdapter]]
- managing, building, updating and recording models, this is done through the [[Model]] API and extensions thereof
- Methods and workflows. This is where most of the heavy work is done in HydroMT. These are functionalities such as transformations on grid, and vector data, delineation of hydrological basins, conversion of land use-land-cover to model parameter maps, and more.  There is not necessarily one way to access these as there are with the [[DataAdapter]] or [[Model]] APIs, instead they are defined where it makes most sense. 
- Cataloging and tracing the use of data, which is mostly done through the [[DataCatalog]]

Core also provides functionality to [[config |configure]] all of these functionalities so the plugins don't have to worry about this 

 [[entrypoints]] 