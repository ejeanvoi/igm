### <h1 align="center" id="title">IGM module load_tif_data </h1>

# Description:

This IGM module loads input spatial fields from tiff file. You may select
available fields in variables you need at least topg or usurf, and thk,
filed e.g. topg.tif, thk.tif must be present in the working forlder.

The module takes tiff files input and return variables contained inside as tensorflow objects
 
# Parameters: 


|short|long|default|help|
| :--- | :--- | :--- | :--- |
|`-h`|`--help`||show this help message and exit|
||`--crop_data`|`False`|Crop the data with xmin, xmax, ymin, ymax (default: False)|
||`--crop_xmin`|`None`|crop_xmin|
||`--crop_xmax`|`None`|crop_xmax|
||`--crop_ymin`|`None`|crop_ymin|
||`--crop_ymax`|`None`|crop_ymax|