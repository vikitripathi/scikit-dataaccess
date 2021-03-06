<p align="left">
  <img alt="Scikit Data Access" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/skdaccess_logo360x100.png"/>
</p>

- Import scientific data from various sources through one easy Python API.
- Use iterator patterns for each data source (configurable data generators + functions to get next data chunk).
- Skip parser programming and file format handling.
- Enjoy a common namespace for all data and unleash the power of data fusion.
- Handle data distribution in different modes: (1) local download, (2) caching of accessed data, or (3) online stream access
- Easily pull data on cloud servers through Python scripts and facilitate large-scale parallel processing.
- Build on an extensible plattform: Adding access to a new data source only requires addition of its "DataFetcher.py".   
- Open source (MIT License)

<p align="center">
  <img alt="Scikit Data Access Overview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/skdaccess_overviewdiag.png" width="810"/>
</p>

Supported data sets <sub>(For updates, follow https://twitter.com/scikit_data and https://twitter.com/mithaystack)</sub>


| Namespace  | Description | Preview | Data Source |
| ------------- | ------------- |------------- |------------- |
| <sup> <nobr><img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_astro.png>&#x2060;astro.kepler&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;&#160;</sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nasa.png" /> <sup> Light curves for stars imaged by the NASA Kepler Space Telescope</sup>   | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Kepler.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.astro.kepler.png"/></a>| <sup> https://keplerscience.arc.nasa.gov </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_astro.png> astro.voyager </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nasa.png" /> <sup> Data from the Voyager mission </sup>   | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Voyager.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.astro.voyager.png"/></a>| <sup> https://spdf.gsfc.nasa.gov/ </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.groundwater </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_usgs.png" /> <sup> United States groundwater monitoring wells measuring the depth to water level </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Groundwater.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.groundwater.png"/></a>|<sup> https://waterservices.usgs.gov </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.pbo </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_unavco.png" /> <sup> EarthScope - Plate Boundary Observatory (PBO): Daily GPS displacement time series measurements throughout the United States </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_PBO.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.pbo.png"/></a>|<sup> http://www.unavco.org/projects/major-projects/pbo/pbo.html</sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.grace </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nasa.png" /> <sup> NASA GRACE Tellus Monthly Mass Grids. 30-day measurements of changes in Earth’s gravity field to quantify equivalent water thickness </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_GRACE.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.grace.png"/></a>|<sup> https://grace.jpl.nasa.gov/data/get-data/monthly-mass-grids-land </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.gldas </sup>  | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nasa.png" /> <sup> Land hydrology model produced by NASA. This version of the data is generated to match the GRACE temporal and spatial characteristics and is available as a complementary data product </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_GLDAS.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.gldas.png"/></a>|<sup> https://grace.jpl.nasa.gov/data/get-data/land-water-content </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.modis </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nasa.png" /> <sup> Spectroradiometer aboard the NASA Terra and Aqua image satellites. Generates approximately daily images of the Earth’s surface </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_MODIS.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.modis.png"/></a>|<sup> https://modis.gsfc.nasa.gov </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.magnetometer </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_usgs.png" /> <sup> Data collected at magnetic observatories operated by the U.S. Geological Survey</sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Magnetometer.ipynb"><img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.magnetometer.png"/></a>|<sup> https://geomag.usgs.gov </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.mahali.rinex </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_mit.png" /> <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nsf.png" /> <sup> Rinex files from the MIT led NSF project studying the Earth’s ionosphere with GPS </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Mahali_Rinex.ipynb"> <img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.mahali.rinex.png"/></a> |<sup> http://mahali.mit.edu </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.mahali.tec </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_mit.png" /> <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nsf.png" /> <sup> Total Electron Content from the MIT led NSF project studying the Earth’s ionosphere with GPS </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Mahali_TEC.ipynb"> <img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.mahali.tec.png"/></a>|<sup> http://mahali.mit.edu </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_geo.png>   geo.mahali.temperature </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_mit.png" /> <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nsf.png" /> <sup> Temperature data from the MIT led NSF project studying the Earth’s ionosphere with GPS </sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_Mahali_Temperature.ipynb"> <img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.geo.mahali.temperature.png"/></a> |<sup> http://mahali.mit.edu </sup> |
| <sup> <img src=https://github.com/MITHaystack/scikit-dataaccess/raw/master/skdaccess/docs/images/icon_solar.png> solar.sdo </sup> | <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_datasource_logo_nasa.png" /> <sup> Images from the Solar Dynamics Observatory</sup> | <a href="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/examples/Demo_SDO.ipynb"> <img alt="Preview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/icon_skdaccess.solar.sdo.png"/></a>| <sup> https://sdo.gsfc.nasa.gov/ </sup> |



### Install
```python
pip install scikit-dataaccess
```

### Documentation

- User Manual: [/docs/skdaccess_manual.pdf](https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/skdaccess_manual.pdf)<br>
- Code documentation (Doxygen): [/docs/skdaccess_doxygen.pdf](https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/skdaccess_doxygen.pdf)
- Code visualization (treemap): [/docs/skdaccess_treemap.png](https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/skdaccess_treemap.png)
- Code class diagrams: [/docs/class_diagrams](https://github.com/MITHaystack/scikit-dataaccess/tree/master/skdaccess/docs/class_diagrams)


### Contributors

Project lead: [Victor Pankratius (MIT)](http://www.victorpankratius.com)<br>
Project developers: Cody M. Rude, Justin D. Li, David M. Blair, Michael G. Gowanlock, Victor Pankratius

New contributors welcome! Contact <img src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/skdaccess_cont.png" /> to contribute and add interface code for your own datasets :smile:

  
### Acknowledgements

We acknowledge support from NASA AISTNNX15AG84G, NSF ACI1442997, and NSF AGS-1343967.

## Examples

Code examples (Jupyter notebooks) for all datasets listed above are available at: [/skdaccess/examples](https://github.com/MITHaystack/scikit-dataaccess/tree/master/skdaccess/examples)

<p align="center">
  <img alt="Scikit Data Access Overview" src="https://github.com/MITHaystack/scikit-dataaccess/blob/master/skdaccess/docs/images/skdaccess-quickexamples-combined.png"/>
</p>
