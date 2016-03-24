# A collection of Data Visualization design patterns

English | [Japanese](https://github.com/ynunokawa/data-viz/blob/gh-pages/README_ja.md)

A collection of simple examples to visualize data with charts, maps and events.
Charts are built with D3.js and maps are Leaflet or ArcGIS API for JavaScript.
They provide some inspirations for Data Visualization!

They are created based on our hypothesis of method for Data Visualization as the below.

__(Map + Chart) * Event = Data Visualization ?__

## Mapping

Leaflet or ArcGIS API for JavaScript? I will use both depending on the case.

WHY do I use __[Leaflet](http://leafletjs.com/)__?

* Simple
* Popular
* Light weight
* Not depend on third-party JavaScript library
* Various [plugins](http://leafletjs.com/plugins.html)

WHY do I use __[ArcGIS API for JavaScript](https://developers.arcgis.com/javascript/)__?

* Esri [Web Map](http://esrijapan.github.io/arcgis-dev-resources/create-webmap/)
* No need to write codes to create map and layers
* No need to write codes to change some states of map
* No need to write codes to change some styles of layers
* Various [esri/renderers](https://developers.arcgis.com/javascript/jshelp/intro_bettermaps.html) classes for styling layers

## Chart

WHY do I use __[D3.js](https://d3js.org/)__?

* Lovin' it!

## Event

WHAT is events?

* DOM events (click, hover..)
* Form to input your status
* Time Animation
* etc..

## License
MIT.
