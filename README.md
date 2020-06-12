# waterdata
Tuesday tutorials: data access, time series and spatial data analyses

### These spatial data analyis notebooks cover:
1. indexing/selecting in multi-dimensional arrays (numpy)
2. labeled n-dimensional arrays (xarray)
3. accessing gridded DayMet data, and visualizing gridded data (xarray, matplotlib, cartopy? rioxarray?)
4. computing statistics/aggregation (xarray)

## Materials to draw from

### WHW19 tutorials
- [Data access and time-series statistics cyberseminar](https://github.com/waterhackweek/tsdata_access)
- [Gridded climate data(sets) cyberseminar](https://github.com/waterhackweek/gridded_data)
- [Observatory for Gridded Hydrometeorology (OGH)?](https://github.com/waterhackweek/OGH_group_tutorial) See also [this OGH presentation.](https://github.com/Freshwater-Initiative/OGH_group_tutorial/blob/master/intro_to_ogh.pdf)

### Other resources
- GHW19 vector tools. https://geohackweek.github.io/vector/
- GHW19 raster tools. https://github.com/geohackweek/raster-2019
- OHW19 tutorials: https://oceanhackweek.github.io/ohw19/curriculum_2019.html 

## Yakima watershed focus: Upper Yakima (HUC8 code: 17030001)
For a quick and easy exploration of this watershed (or any other HUC in the lower 48), you can go to https://modelmywatershed.org, an application I've been involved in. Type "upper yakima" in the text box in the upper right, select the HUC 8 Upper Yakima entry, then click on the Select button that comes up. You can add geospatial context via the Layers box (streams/grids/boundaries), and get quick view of the distribution of general watershed properties (precip/air temp/elev/slope/stream order) on the column to the left.

## Setting up the conda environment

```bash
conda env create -f environment.yml
conda activate whwwaterdata; ipython kernel install --user --name whwwaterdata
```
