# Platform-Specific Notes

## OpenLayers

- Version: 7.2.2
- For geometry transformations in polar projections, include [proj4js](http://trac.osgeo.org/proj4js) version 2 (examples use 2.8.1).
- Vector tile examples use [Mapbox Vector Tiles](https://docs.mapbox.com/vector-tiles/specification/).

## Leaflet

- Version: 1.9.3
- Polar projections require [Proj4Leaflet](https://github.com/kartena/Proj4Leaflet) plugin (examples use 1.0.1).
- [Tile gap workaround](https://github.com/Leaflet/Leaflet/issues/3575) available.

## Cesium

- Version: 1.102
- For EPSG:4326 endpoint, use [GeographicTilingScheme](https://github.com/nasa-gibs/gibs-web-examples/blob/master/examples/cesium/gibs.js).

## Mapbox GL

- Version: 1.13.3

## Maplibre GL

- Version: 2.4.0

## Bing Maps

- Uses Bing Maps Control version 8.
- Requires an API key.

## Google Maps

- Uses Google Maps API version 3.
- Requires an API key.