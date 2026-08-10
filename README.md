# Wall Township Roads at Risk

Static GitHub Pages app for drawing road and cross-section profiles through the Wall Township municipal DEM.

The interface follows the North Wildwood Roads at Risk reference: threshold presets, NAVD88/MLLW conversion, terrain and hillshade views, saved multi-line cross sections, flood-history and future-frequency charts, and CSV/Shapefile exports.

Municipal constants:

- Observations: USGS 01408048, Manasquan
- PETSS / NOAA station: 8532591
- NAVD88 thresholds: 3.33 ft minor, 4.33 ft moderate, 5.33 ft major
- MLLW thresholds: 5.7 ft minor, 6.7 ft moderate, 7.7 ft major
- MLLW = NAVD88 + 2.37 ft

Terrain source: USGS 3DEP Bare Earth DEM Dynamic ImageServer, clipped to the Wall Township boundary at 13.7-foot adaptive resolution.
