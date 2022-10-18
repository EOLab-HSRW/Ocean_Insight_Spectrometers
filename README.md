
### EO-LAB Ocean Insight Spectrometers

### Folder Structure:
* examples:
  * Jupyter Notebook example codes for our Ocean Insight spectrometers 

* calibration_files
  * Irradiance calibration files
  * the filenames are in the following format:
  * [spectrometer model and number] _ irradCal _ [calibration date in YYYYMMDD] _ [fiber optic cable diameter] _ [optional: combined].cal
  * example: red-tide-#1_irradCal_20220929_200u_combined
  * the optional "combined" tag is used when the calibration was done with a combined light sources (Halogen and Deterium lamps)

### PySeaBreeze package installation
Github: https://github.com/ap--/python-seabreeze

Docs: https://python-seabreeze.readthedocs.io/en/latest/backend_api.html

!!  The Red-Tide spectrometers cant be used with pyseabreeze due to some firmware limitations of the spectrometers. Use Ocean View instead.

#### Installation:
Conda:

    conda install -c conda-forge seabreeze
    seabreeze_os_setup

Python PIP:

    pip install seabreeze
    seabreeze_os_setup

!! Make sure to run “seabreeze_os_setup” after the installation

### Additional information can be found on our EO-LAB spectrometer page: 

https://wiki.eolab.de/doku.php?id=eolab:spectrometer:start
