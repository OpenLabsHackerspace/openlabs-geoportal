# OpenLabs GeoPortal

This GeoPortal displays the data from the Municipality of Tirana.

## Data

**All the data come from the Municipality of Tirana !**

- Ndertesa (2017) (*buildings*)  
- Rruge Akse Tirana (2017-01-31) (*streets*)  
- Rruge Akse ExKomuna  
- Njesite Administrative Ndertesat (*administrative buildings*)
- Stacione & Linjat Qytetese 2018 (*public transport: stations + lines*)  
:octocat: Source: [bashkiatirane/Harta-e-Transportit-Publik](https://github.com/bashkiatirane/Harta-e-Transportit-Publik/tree/master/Stacione%20%26%20Linjat%20Qytetese%202018)

## Demo

https://geoportal.openlabs.cc/#map=15/19.825443/41.326593

## Install

See [INSTALL.md](INSTALL.md)

## Usage

### iD Editor

<https://www.openstreetmap.org/edit?editor=id>

- Open *Background Settings* (shortcut: `B`)
- Click on *Custom*
- Paste `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/tirana@GoogleMapsCompatibleExtended/{z}/{x}/{-y}.png`    
- Click on OK

**Update March 2018: This layer will be soon available in iD default settings !**

### JOSM

<https://josm.openstreetmap.de/>

The layer is available in the default "Imagery preferences" as :

- [*Municipality of Tirana (Open Labs GeoPortal)*](https://josm.openstreetmap.de/wiki/Maps/Albania#MunicipalityofTiranaOpenLabsGeoPortal)
- [*Municipality of Tirana - Public Transport (Open Labs GeoPortal) (overlay)*](https://josm.openstreetmap.de/wiki/Maps/Albania#MunicipalityofTirana-PublicTransportOpenLabsGeoPortaloverlay)

More information on how to enable it : <https://josm.openstreetmap.de/wiki/Help/Preferences/Imagery> !

| Type | URL |
|------|-----|
| WMS | `https://geoportal.openlabs.cc/mapcache/` |
| TMS - Full  | `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/tirana@GoogleMapsCompatibleExtended/{z}/{x}/{-y}.png` |
| TMS - Public Transport | `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/public-transport@GoogleMapsCompatibleExtended/{z}/{x}/{-y}.png` |

### QGIS

<https://qgis.org/>

| Type | URL |
|------|-----|
| WMS | `https://geoportal.openlabs.cc/mapcache/` |
| TMS - Full  | `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/tirana@GoogleMapsCompatibleExtended/{z}/{x}/{-y}.png` |
| TMS - Public Transport | `https://geoportal.openlabs.cc/mapcache/tms/1.0.0/public-transport@GoogleMapsCompatibleExtended/{z}/{x}/{-y}.png` |
