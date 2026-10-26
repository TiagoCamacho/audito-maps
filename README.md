# Audito maps

Offline map of Portugal (mainland, Madeira and the Azores) used by the Audito app.

Each release (`map-YYYYMMDD`) has:

| File | What |
|---|---|
| `portugal.pmtiles` | Vector map tiles up to zoom 15 ([PMTiles](https://github.com/protomaps/PMTiles)), cut from a [Protomaps](https://protomaps.com) daily build |
| `portugal-addresses.json.gz` | Address search index: streets, door numbers and places |
| `manifest.json` | Date of the data, size and SHA-256 of each file |

## Licence and credit

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).

`portugal-addresses.json.gz` is a derived database of OpenStreetMap data and is also made available under the
ODbL 1.0. It was produced from the [Geofabrik](https://download.geofabrik.de/europe/portugal.html) extract of
Portugal by keeping named streets (one point per street section), addresses with a door number, and named
places, each with the nearest town or village.

`portugal.pmtiles` is an extract of the Protomaps basemap, which is built from OpenStreetMap data (ODbL) and
other open sources listed at [docs.protomaps.com](https://docs.protomaps.com/basemaps/downloads).
