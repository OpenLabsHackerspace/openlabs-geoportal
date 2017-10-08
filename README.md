# OpenLabs GeoPortal 

This GeoPortal displays the data from the Municipality of Tirana.

## Demo

http://149.202.183.195/map.html#map=15/19.825443/41.326593

## Install

See [INSTALL.md](INSTALL.md)

## Usage

### QGIS

<https://qgis.org/>

#### WMS

    http://149.202.183.195/mapcache/

### JOSM 

<https://josm.openstreetmap.de/>

#### WMS

    wms:http://149.202.183.195/mapcache/?FORMAT=image/png&VERSION=1.1.1&SERVICE=WMS&REQUEST=GetMap&LAYERS=tirana&STYLES=&SRS={proj}&WIDTH={width}&HEIGHT={height}&BBOX={bbox}

#### TMS

    tms:http://149.202.183.195/mapcache/tms/1.0.0/tirana@GoogleMapsCompatible/{z}/{x}/{-y}.png
