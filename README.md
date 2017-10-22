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

![Streets legend](https://geoportal.openlabs.cc/cgi-bin/mapserv?map=/home/ubuntu/openlabs-geoportal/mapserver/tirana.map&version=1.3.0&service=WMS&request=GetLegendGraphic&sld_version=1.1.0&layer=streets&format=image/png&STYLE=default "Streets legend")

## Demo

https://geoportal.openlabs.cc/#map=15/19.825443/41.326593

## Install

See [INSTALL.md](INSTALL.md)

## Usage

### QGIS

<https://qgis.org/>

| Type | URL |
|------|-----|
| WMS  | `https://geoportal.openlabs.cc/mapcache/` |
    
### iD Editor

<https://www.openstreetmap.org/edit?editor=id>

- Open *Background Settings* (shortcut: `B`)
- Click on *Custom*
- Paste `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/tirana@GoogleMapsCompatible/{z}/{x}/{-y}.png`    
- Click on OK

### JOSM 

<https://josm.openstreetmap.de/>

The layer is available in the default "Imagery preferences" as "[*Municipality of Tirana (Open Labs GeoPortal)*](https://josm.openstreetmap.de/wiki/Maps/Albania)" !  
More information on how to enable it : <https://josm.openstreetmap.de/wiki/Help/Preferences/Imagery> !

| Type | URL                                                                                             |
|------|-------------------------------------------------------------------------------------------------|
| WMS  | `https://geoportal.openlabs.cc/mapcache/`                                                       |
| TMS  | `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/tirana@GoogleMapsCompatible/{z}/{x}/{-y}.png` |
