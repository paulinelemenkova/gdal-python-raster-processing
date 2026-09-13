# GDAL + Python: Installation Notes and Useful Raster Commands

A concise, reproducible quick-reference for setting up **GDAL** alongside a
scientific **Python** stack on macOS, and for inspecting geospatial raster data
from the command line. Collected while configuring a GIS / remote-sensing
environment for bathymetric and topographic analysis.

## Contents

- \`GDAL-01-scripts.sh\` - installation notes (Homebrew/conda) and a set of
  \`gdalinfo\` commands for reading raster metadata, statistics, histograms and
  projection information from a NetCDF grid.
- \`jupiter re-install path.py\`, \`tryloop.py\` - short Python environment and
  path-handling snippets.

## Technologies

Shell, Python and [GDAL](https://gdal.org/) (NetCDF / GeoTIFF raster I/O).

## Usage

Read the scripts as a reference, or adapt the \`gdalinfo\` calls to your own
raster files. Paths and dataset names are examples and should be edited for your
system.

## Author

**Polina Lemenkova**  
ORCID: https://orcid.org/0000-0002-5759-1089

## License

Released under the MIT License (see `LICENSE`).

## Reuse

These materials were written as programming exercises and are shared as open,
self-contained teaching examples. If they are useful in your own teaching or
research, a link back to this repository and to the author's ORCID is appreciated.
