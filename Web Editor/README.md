# Eurac openEO examples

## Examples using the Web Editor

Clicking on the provided links will open an openEO Web Editor session showing the example process graph.
You must log-in before starting any batch processing or download some data.

### 1. Load and save netCDF

This examples shows the most basic usage of openEO for data access.
It loads the RGB bands (B04,B03,B02) from the Sentinel-2 L2A collection over the Alps `S2_L2A_ALPS` from the area of Bolzano (Italy) and saves the result as a netCDF.

https://editor.openeo.org/?server=https://openeo.eurac.edu&process=https://raw.githubusercontent.com/clausmichele/eurac-openeo-examples/main/Web+Editor/bolzano_S2_load_save_netcdf.json&discover=1

### 2. Median temporal RGB composite PNG

It loads the RGB bands (B04,B03,B02) from the Sentinel-2 L2A collection over the Alps `S2_L2A_ALPS` from the area of Bolzano (Italy). It takes the median over time and saves the result as a PNG for a direct visualization.

https://editor.openeo.org/?server=https://openeo.eurac.edu&process=https://raw.githubusercontent.com/clausmichele/eurac-openeo-examples/main/Web+Editor/bolzano_median_rgb_png.json&discover=1

### 3. Median temporal RGB composite geoTIFF

It loads the RGB bands (B04,B03,B02) from the Sentinel-2 L2A collection over the Alps `S2_L2A_ALPS` from the area of Bolzano (Italy). It takes the median over time and saves the result as a geoTIFF for a direct visualization over a reference map.

https://editor.openeo.org/?server=https://openeo.eurac.edu&process=https://raw.githubusercontent.com/clausmichele/eurac-openeo-examples/main/Web+Editor/bolzano_median_rgb_geotiff.json&discover=1

### 4. Yearly average NDVI timeseries JSON

It loads the red and nir bands (B04,B08) from the Sentinel-2 L2A collection over the Alps `S2_L2A_ALPS`. It computes the NDVI: (NIR - RED) / (NIR + RED), takes the mean over a sample area and saves the result as a JSON file for a direct visualization.

https://editor.openeo.org/?server=https://openeo.eurac.edu&process=https://raw.githubusercontent.com/clausmichele/eurac-openeo-examples/main/Web+Editor/NDVI_year_timeseries_json.json&discover=1

### 5. Summer median NDVI geoTIFF

It loads the red and nir bands (B04,B08) from the Sentinel-2 L2A collection over the Alps `S2_L2A_ALPS`. It computes the NDVI: (NIR - RED) / (NIR + RED), takes the median over a the summer months and saves the result as a geoTIFF.

https://editor.openeo.org/?server=https://openeo.eurac.edu&process=https://raw.githubusercontent.com/clausmichele/eurac-openeo-examples/main/Web+Editor/bolzano_median_summer_NDVI_geotiff.json&discover=1

