\# Super-Eje Search Plugin (QGIS)



A QGIS plugin to search features along a "super-eje" (main corridor / axis)

using a buffer distance and attribute filters. Generic version built with

public and synthetic data — no proprietary data included.



\## Problem



Locating every parcel, asset, or point that intersects a main corridor

(road, feeder line, pipeline) required manual zooming and selection in QGIS.

On a typical dataset this took \*\*\~4 hours\*\* of tedious work and was

error-prone.



\## Solution



A plugin that:

\- Takes a selected line layer as the corridor ("super-eje").

\- Applies a configurable buffer (default 50 m).

\- Filters intersecting features by attribute (e.g., status, type).

\- Exports results to a new layer / CSV.



\## Result



Manual workflow reduced from \*\*\~4 h to \~45 min\*\* (≈5× faster), with

reproducible, auditable selections.



\## Demo



!\[Demo](docs/demo.png)



\## Installation (3 steps)



1\. Download the latest `.zip` from \*\*Releases\*\*.

2\. In QGIS: `Plugins → Manage and Install Plugins → Install from ZIP`.

3\. Enable \*\*Super-Eje Search\*\* in the toolbar and select a line layer.



\## Stack



\- Python 3 · PyQGIS (QGIS 3.x API)

\- Shapely / GeoPandas for geometry ops

\- Public sample data: IGAC open data \& OpenStreetMap



\## License



MIT — see \[LICENSE](LICENSE).



> Data disclaimer: this repository uses only public (IGAC, OpenStreetMap)

> or synthetic data. No proprietary or corporate data is included.

