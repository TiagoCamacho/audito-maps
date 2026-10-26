# Audito maps

Offline map of Portugal (mainland, Madeira and the Azores).

| File | What | Release |
|---|---|---|
| `portugal.pmtiles` | Vector map tiles up to zoom 15 ([PMTiles](https://github.com/protomaps/PMTiles)), cut from a [Protomaps](https://protomaps.com) daily build | `map-YYYYMMDD` |
| `portugal-addresses.json.gz` | Address search index: streets, door numbers (with postcode where known) and places | `data-YYYYMMDD` |
| `portugal-freguesias.json.gz` | Boundaries of the freguesias (CAOP 2025, simplified) | `data-YYYYMMDD` |
| `portugal-coast.json.gz` | Coastline, for the distance to the coast | `data-YYYYMMDD` |
| `portugal-altitude.bin` | Altitude, 90 m grid (Copernicus WorldDEM™-90) | `data-YYYYMMDD` |
| `manifest.json` | Date of the data, release, size and SHA-256 of each file | each release |

## Licence and credit

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright), available under the
[Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).

`portugal-addresses.json.gz` and `portugal-coast.json.gz` are derived databases of OpenStreetMap data and are
also made available under the ODbL 1.0. They were produced from the
[Geofabrik](https://download.geofabrik.de/europe/portugal.html) extract of Portugal: named streets (one point
per street section), addresses with a door number and their postcode, named places with the nearest town or
village, and the `natural=coastline` lines simplified to about 20 m.

`portugal.pmtiles` is an extract of the Protomaps basemap, which is built from OpenStreetMap data (ODbL) and
other open sources listed at [docs.protomaps.com](https://docs.protomaps.com/basemaps/downloads).

`portugal-freguesias.json.gz` is derived from the [Aldeias Portuguesas](https://aldeiasportuguesas.pt/fr/donnees/)
dataset (CAOP 2025 of the [Direção-Geral do Território](https://www.dgterritorio.gov.pt/), simplified), available
under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/); this file is shared under the same licence.

`portugal-altitude.bin`: produced using Copernicus WorldDEM™-90 © DLR e.V. 2010-2014 and © Airbus Defence and
Space GmbH 2014-2018 provided under COPERNICUS by the European Union and ESA; all rights reserved.
The organisations in charge of the Copernicus programme by law or by delegation do not incur any liability for
any use of the Copernicus WorldDEM™-90. Anyone redistributing this file must keep these notices and is bound by
the same obligations of the [Copernicus WorldDEM™-90 licence](https://dataspace.copernicus.eu/explore-data/data-collections/copernicus-contributing-missions/collections-description/COP-DEM).
This product is not endorsed by the Copernicus programme, ESA, the European Union or Airbus.
