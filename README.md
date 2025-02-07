# MapServer DGT

MapServer DGT is a specialized implementation of [MapServer](https://mapserver.org/), an open-source platform for publishing spatial data and creating interactive mapping applications on the web. This repository focuses on [DGT](https://www.dgt.gov.pt/) (Direção-Geral do Território) specific configurations and data integrations.

## Features

- **Advanced Cartographic Output**: Leverages MapServer's capabilities for scale-dependent feature rendering, feature labeling with collision mediation, TrueType font support, and thematic mapping using logical or regular expression-based classes.

- **Support for Multiple Data Formats**: Utilizes the GDAL/OGR library to support a wide range of vector and raster data formats, including ESRI Shapefiles, PostGIS, Oracle Spatial, and many others. :contentReference[oaicite:0]{index=0}

- **Map Projection Support**: Provides on-the-fly map projection with thousands of projections through the Proj.4 library.

## Installation

To set up MapServer DGT, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/PascalLike/mapserver-dgt.git
   cd mapserver-dgt
