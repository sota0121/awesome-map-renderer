# digital-maps
Technology of rendering digital maps on browser

# classify
- Map(or Maps API) provider 2D and 3D
  - Google Maps(Google Maps Platform)
  - Bing Maps
  - MapBox
  - OpenStreetMap
  - Cesium ion(3D content) --> <font color=orange>instead of Google Earth</font>
- Library for rendering Maps(or tile object like maps)
  - leaflet.js
  - OpenLayers
- for example ...
  - leaflet + BingMaps
  - leaflet + MapBox
  - leaflet + OpenStreetMap
  - OpenLayers + BingMaps ... etc
  - <strong><font color=red>note >> Google Maps must be accessed with GoogleMapsAPI</font></strong>
- Library for world-class 3D globes and maps(3D visualization not only map but also general 3D data)
  - CesiumJS

# table of contents
- map2d
  - library for creating interactive maps on the web
    - [leafletjs](https://leafletjs.com/)
      - map source is osm
      - [leafletjs-github](https://github.com/Leaflet/Leaflet)
    - [leaflet-osm](https://github.com/openstreetmap/leaflet-osm)
      - Leaflet plugin for rendering tile and vector data from openstreetmap.org
      - with api key
    - [openlayers](https://github.com/openlayers/openlayers)
  - service for creating customized maps on the web
    - [mapbox & mapbox studio](https://www.mapbox.com/)
      - map source is osm
      - create your style on mapbox studio
      - creating maps in your style on the web or native app
      - ref >> [here!!](https://paiza.hatenablog.com/entry/2017/12/07/JavaScript%E3%81%A7%E5%88%B6%E5%BE%A1%E3%81%A7%E3%81%8D%E3%82%8BWeb%E3%83%99%E3%83%BC%E3%82%B9%E3%81%AE%E4%B8%87%E8%83%BD%E3%83%9E%E3%83%83%E3%83%97%E3%82%A8%E3%83%87%E3%82%A3%E3%82%BF%E3%80%8CMapbox_Stud)
- map3d
  - [cesiumjs](https://cesiumjs.org/)
    - [github](https://github.com/AnalyticalGraphicsInc/cesium)
  - [ol-cesiumjs](https://openlayers.org/ol-cesium/)
    - OpenLayers - Cesium **integration** library.
    - [github](https://github.com/openlayers/ol-cesium)
  - [osm-3d](http://www.osm-3d.org/map.htm)
  - [osm-buildings](https://osmbuildings.org/)
    - OSM Buildings is a library for visualizing 3d building geometry.
    - [github](https://github.com/OSMBuildings/OSMBuildings)
    - 1. using osmbuildings api
    - 2. using leaflet
    - 3. using mapbox gl
  - [vizicities](http://ww.vizicities.com/)
    - [github](https://github.com/robhawkes/vizicities)
  - [eeGeojs](https://www.wrld3d.com/wrld.js/latest/docs/examples/)


