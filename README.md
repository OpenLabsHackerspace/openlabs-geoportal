# OpenLabs GeoPortal 

This GeoPortal displays the data from the Municipality of Tirana.

## Data

### Ndertesa (2017) (*buildings*)

| Name       | | *Example*       |
|------------|-|-----------------|
| OBJECTID   | | *18674*         |
| AdmUnit    | | *TIRANA*        |
| Floors     | | *4*             |
| Nj_Adm     | |                 |
| NrKat      | | *0*             |
| Shape_Leng | | *489.347958771* |
| Shape_Area | | *4352.91150748* |

### Rruge Akse Tirana (2017-01-31) (*streets*)

| Name       |             | *Example*            |
|------------|-------------|----------------------|
| EMRI       | Name        | *BLV. ZOGU 1*        |
| KODI       | Code        | *200*                |
| NJESIA     | Unit        | *Njesia Bashkiake 9* |
| Kategoria  | Category    | *URBANE KRYESORE*    |
| KODI_TEXT  | Code (text) | *200*                |
| Shape_Leng |             | *140.12453194*       |
| N_13042014 |             | *0*                  |

## Demo

http://149.202.183.195/map.html#map=15/19.825443/41.326593

## Install

See [INSTALL.md](INSTALL.md)

## Usage

### QGIS

<https://qgis.org/>

#### WMS

    http://149.202.183.195/mapcache/
    
### iD Editor

<https://www.openstreetmap.org/edit?editor=id>

- Open *Background Settings* (shortcut: `B`)
- Click on *Custom*
- Paste `http://149.202.183.195/mapcache/tms/1.0.0/tirana@GoogleMapsCompatible/{z}/{x}/{-y}.png`    
- Click on OK

### JOSM 

<https://josm.openstreetmap.de/>

#### WMS

    wms:http://149.202.183.195/mapcache/?FORMAT=image/png&VERSION=1.1.1&SERVICE=WMS&REQUEST=GetMap&LAYERS=tirana&STYLES=&SRS={proj}&WIDTH={width}&HEIGHT={height}&BBOX={bbox}

#### TMS

    tms:http://149.202.183.195/mapcache/tms/1.0.0/tirana@GoogleMapsCompatible/{z}/{x}/{-y}.png
