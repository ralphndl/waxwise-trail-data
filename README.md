# WaxWise public trail data

Versioned OpenStreetMap trail extracts for the WaxWise region editor.
Downloads are attached to tagged GitHub releases; application code and user data are not included.

## Licence and attribution

© OpenStreetMap contributors; derived database and modifications by WaxWise.
This database is made available under the Open Data Commons Open Database License (ODbL) 1.0:
https://opendatacommons.org/licenses/odbl/1-0/
Any rights in individual contents are licensed under the Database Contents License:
https://opendatacommons.org/licenses/dbcl/1-0/
Source and contributor information: https://www.openstreetmap.org/copyright

## Contents

The archive contains only a public trail catalogue, OSM-derived places and spatial trail files.
Countries: Austria, Finland, Germany, Italy, Liechtenstein, Norway and Sweden.
Ways are split into approximately 80 m sections. Coordinates are rounded to six decimal places.
No account identifiers, private regions, user-uploaded GPX files or credentials are included.

`trail-static/current.json` selects the active immutable dataset. Each version has a gzipped JSON
manifest, tile files and place-prefix files. Older dataset versions remain present for saved selections.
A tile row is `[segmentId, startLongitudeE6, startLatitudeE6, endLongitudeE6, endLatitudeE6]`.
Segment IDs contain OSM way ID, source edge index and subdivision index separated by colons.

The entire derivative data is available in the release archive. Verify the published SHA-256 before extracting.
