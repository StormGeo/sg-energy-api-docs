![](images/stormgeo-logo-black-rgb.svg)

# Tutorials and Power Query scripts/connector for the StormGeo Energy API.

Here you will find material related to the StormGeo Energy API. This included an interactive python notebook tutorial that will teach you how to use the
StormGeo API with Python and JupyterLab. You will also find Power Query scripts to connect the StormGeo API with Excel and the Power BI connector.

To get the files in this repository:

1. Clone the repository or download it as a zip file. (Click on "Code" and "Download Zip")

## Power Query

Please see the [API documentation](https://docs.nena.no/energyapi/) on how to setup [Power Query](https://learn.microsoft.com/en-us/power-query/power-query-what-is-power-query) in Excel and PowerBI.

## Jupyter Notebook tutorial and python module.

The notebook tutorials can be found in the Tutorials folder. It contains the following files:

- **StormGeoAPI-Tutorial.ipynb** - An interactive tutorial on how to use the StormGeo API
- **dk_wind_power.ipynb** - Tutorial on how to plot Danish wind power with data from the StormGeo API
- **no_hydro_filling.ipynb** - Tutorial on how to plot Norwegian reservoir filling with data from the StormGeo API

In addition, this folder has the python module:

- **StormGeo_api.py** <br>

with pre-implemented python functions for requesting data from the StormGeo API

### Requirements

You will need the following packages to run the notebook tutorials:

- JupyterLab
- Python3
- Pandas
- Bokeh
- Matplotlib

The easiest way to get these is by using a default installation of [Anaconda](https://www.anaconda.com/).

## API Limitations

Here is listed a few important limitations in the API that any user should be aware of.

- Due to limitations in the API, there are 24 hour values in both DST clock change days, with the missing hour being averaged into 02:00 for autumn, and an interpolated extra hour on the spring clock change

## Contact

If you have any questions, please don't hesitate to contact us at
StormGeo@stormgeo.com
