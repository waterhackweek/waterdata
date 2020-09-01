# Tuesday tutorials: data access, time series and spatial data analyses

## Tutorials

1. Introduction: Water data, Python and You (presentation) - Bart Nijssen
2. Access and analyze point time series data ([notebook](point_data_tutorial.ipynb)) - Yifan Cheng
3. Access and analyze raster and multi-dimensional gridded data - Steven Pestana
    - Notebook 0: [NumPy and the ndarray](gridded_data_tutorial_0.ipynb)
    - Notebook 1: [Introduction to xarray](gridded_data_tutorial_1.ipynb)
    - Notebook 2: [Daymet data access](gridded_data_tutorial_2.ipynb)
    - Notebook 3: [Investigating SWE at Mt. Rainier with Daymet](gridded_data_tutorial_3.ipynb)
4. Water data mash up ([notebook](mashup_waterbudget.ipynb)) - Emilio Mayorga


## Yakima watershed focus: Upper Yakima, HUC8 code 17030001

For a quick and easy exploration of this watershed (or any other HUC in the lower 48), you can go to https://modelmywatershed.org. Type "upper yakima" in the text box in the upper right, select the HUC 8 Upper Yakima entry, then click on the Select button that comes up. You can add geospatial context via the Layers box (streams/grids/boundaries), and get quick view of the distribution of general watershed properties (precip/air temp/elev/slope/stream order) on the column to the left.


## Setting up the conda environment

Use the `environment.yml` file found in this repository.

```bash
conda env create -f environment.yml
conda activate whwwaterdata
```


## Related past materials we are drawing from

### WHW19 tutorials
- [Data access and time-series statistics cyberseminar](https://github.com/waterhackweek/tsdata_access)
- [Gridded climate data(sets) cyberseminar](https://github.com/waterhackweek/gridded_data)
- [Observatory for Gridded Hydrometeorology (OGH)?](https://github.com/waterhackweek/OGH_group_tutorial) See also [this OGH presentation.](https://github.com/Freshwater-Initiative/OGH_group_tutorial/blob/master/intro_to_ogh.pdf). We didn't use this package in these tutorials, but they share goals.

### Other resources
- GeoHackWeek 2019 vector tools. [https://geohackweek.github.io/vector/](https://geohackweek.github.io/vector/)
- GeoHackWeek 2019 raster tools. [https://github.com/geohackweek/raster-2019](https://github.com/geohackweek/raster-2019)
- GeoHackWeek 2020 tutorials: [https://oceanhackweek.github.io/ohw-resources/schedule/](https://oceanhackweek.github.io/ohw-resources/schedule/) and [https://github.com/oceanhackweek/ohw20-tutorials](https://github.com/oceanhackweek/ohw20-tutorials)
