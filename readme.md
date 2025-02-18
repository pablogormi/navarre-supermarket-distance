# Distance to closest supermarket
## Description
This project displays the distance to the closest supermarket in the spanish region of Navarra. The data for the buildings is obtained from the Government of Navarra's public data repositories, while the supermarkets are obtained from OpenStreetMap data. If needed, building data could also be obtained from OpenStreetMap, meaning this code could be theoretically used for anywhere on Earth.

In order to speed up calculation and simplify the visualization, it is limited to a specific region inside Navarra, called a *municipio*. All *municipios* are listed in `municipios.txt` and can be set on the first cell of the notebook. The list and coordinates of the different *municipios* are also obtained from the Government of Navarra's repositories.

Currently the map is saved to a html file, `mapa.html` (the one already uploaded is the result of running the notebook as-is), but it can be directly printed or modified in other ways.

A static version of this repository's `mapa.html` is available [here](https://pablogormi.github.io/navarre-supermarket-distance/mapa.html).

## Requirements

The required libraries are osmnx and geopandas.
