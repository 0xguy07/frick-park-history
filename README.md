# Frick Park History Map

An interactive history map of **Frick Park**, Pittsburgh, Pennsylvania: from the Swisshelm gristmill and the Frick family's woods to the Pope gatehouses, the Cold War gun battery, the Blue Slide, and the Fern Hollow Bridge.

**Open the map:** https://0xguy07.github.io/frick-park-history/

Next door: the [Swisshelm Park History Map](https://0xguy07.github.io/swisshelm-park-history/).

## What's on it

- **Dated events** (before 1750 to 2026) with sources and a location-confidence rating. Events with no single spot ("park-wide") appear in the timeline list only.
- **Historical photographs** (1891–2004), each placed at its estimated location. Public-domain and copyright-undetermined photos are shown on the map; photos still in copyright are marked with hollow dots and open at Historic Pittsburgh.
- **Lost features**: the country club golf course, the 1901 and 1973 Fern Hollow bridges, the anti-aircraft battery, the slag heaps, and more.
- **Today's trails and streams** from OpenStreetMap.
- **Old map overlays**: 1904, 1951, 1960, and 1993 USGS topographic maps; G. M. Hopkins real estate plat maps from 1923 and 1939 (19 plate sections stitched together); and a 1938 aerial photograph, all georeferenced to today's streets.
- The illustrated **1939 Pictorial Map of Frick Park** by Ezra C. Stiles, in its own zoomable viewer (`pictorial-1939.html`).
- A **timeline slider** to view the park as of any year.

## Accuracy notes

- Photo and some event locations are **estimates** based on catalog descriptions; each item shows its confidence.
- The plat sections were each fitted to 3–12 street corners (typical error 2–8 m; up to 10–20 m at a few edges with no surviving streets, such as the old Forward Ave and Commercial St near Nine Mile Run). The seams between sections are visible.
- The 1938 aerial was fitted to six street corners and landmarks (RMS error about 8 m); expect 10–30 m error toward the edges, where the tilt and hills distort a single photograph. The Parkway, drawn on today's base map, did not exist yet.
- Sources sometimes disagree on dates (for example, the park's opening on 25 or 26 June 1927, and the Blue Slide's 1962 or 1963). Where they do, the event text says so.

## Sources and credits

| Material | Source | Rights |
|---|---|---|
| Photographs | Pittsburgh City Photographer Collection (University of Pittsburgh); Allegheny Conference on Community Development Photographs and Hebrew Institute Photographs (Heinz History Center); Frederick J. Osterling Collection; Squirrel Hill Historical Society. All via [Historic Pittsburgh](https://historicpittsburgh.org/) | Shown per each item's rights statement; in-copyright items are linked, not copied |
| Topographic maps | U.S. Geological Survey, Historical Topographic Map Collection | Public domain |
| Plat maps (1923, 1939) | G. M. Hopkins Co., *Real Estate Plat-Books of the City of Pittsburgh*, Vol. 2 (1923 plates 36B–39B; 1939 plates 16, 24, 34), via Historic Pittsburgh | Historic Pittsburgh |
| 1939 pictorial map | Ezra C. Stiles, *Pictorial Map of Frick Park* (Union Trust Co., 1939), [David Rumsey Map Collection](https://www.davidrumsey.com/luna/servlet/detail/RUMSEY~8~1~274129~90047905), David Rumsey Map Center, Stanford Libraries | CC BY-NC-SA 3.0 |
| 1938 aerial | PennPilot, Pennsylvania Geological Survey / PASDA (frame APS-11-105, 25 Sep 1938) | Public domain |
| Trails, streams, streets | © OpenStreetMap contributors | ODbL |
| Park boundary | City of Pittsburgh parks, via WPRDC | Open data |
| Base maps | Esri World Street Map and World Imagery | Esri terms |

Key published sources for the events include the Frick Park City Historic Landmark nomination (Preservation Pittsburgh, 2023), Historic Pittsburgh catalog descriptions, the Historical Marker Database, the NTSB's Fern Hollow Bridge report (2024), the *Pittsburgh Post-Gazette*, and Wikipedia.

## Corrections and contributions

Found an error, have a photo, or remember something about the park? Please [open an issue](https://github.com/0xguy07/frick-park-history/issues).

## Files

- `index.html`: the map (a single page using [Leaflet](https://leafletjs.com/))
- `pictorial-1939.html`: viewer for the 1939 pictorial map
- `frick-park.geojson`: all map data (events, photos, lost features, trails, boundary)
- `assets/`: photographs and georeferenced overlay images
