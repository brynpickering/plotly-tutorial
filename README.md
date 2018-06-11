# Plotly Tutorial for energy system modellers
This repository is for the tutorial on using the Python package Plotly to build beautiful plots for energy system related data, as given in openmod Zurich workshop, June 2018.

# Setup

## 1. Install the Miniconda Python distribution

Download the Miniconda Python distribution from:

https://conda.io/miniconda.html

If you have Anaconda already installed, that's fine! Miniconda is just a slimmer version. Make sure you download the Python 3 version.

## 2. Clone or download this repository

Everything you should need to run this model (except the data) is in this repository. Download or clone it in order to get everything onto your device.

## 3. Create an environment

Once Miniconda is installed, create a new conda environment with the required packages, by running the following command in a terminal (Linux or macOS) or a command-line window (Windows), making sure you run this command inside the directory containing this repository's requirements.yml ﬁle:

``conda env create -f requirements.yml``

## 4. Ensure that you can successfully run a Jupyter Notebook

If you are unfamiliar with the Jupyter Notebook, have a look at this [quick start guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/index.html), in particular the section on [running the notebook](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html). During the tutorial session we will not have time to solve installation problems, so make sure that you are able to run the Jupyter Notebook before you arrive.

## 5. Optional: get mapbox token:

If you would like to visualise your spatial plots on a Mapbox base map then you'll need a Mapbox API token. You can get that by creating a mapbox account: https://www.mapbox.com/

# Data

We are using data made available from the Open Power System Data project for this tutorial. These datasets can be found in the data subdirectory and are based on the following download links:

* [time_series_60min_singleindex.csv](https://data.open-power-system-data.org/index.php?package=time_series&amp;version=2017-07-09&amp;action=customDownload&amp;resource=3&amp;filter%5B_contentfilter_utc_timestamp%5D%5Bfrom%5D=2011-01-01&amp;filter%5B_contentfilter_utc_timestamp%5D%5Bto%5D=2016-12-31&amp;filter%5BRegion%5D%5B%5D=CZ&amp;filter%5BRegion%5D%5B%5D=DE&amp;filter%5BRegion%5D%5B%5D=DK&amp;filter%5BRegion%5D%5B%5D=SE&amp;filter%5BVariable%5D%5B%5D=solar&amp;filter%5BVariable%5D%5B%5D=wind&amp;filter%5BVariable%5D%5B%5D=wind_offshore&amp;filter%5BVariable%5D%5B%5D=wind_onshore&amp;filter%5BAttribute%5D%5B%5D=generation&amp;downloadCSV=Download+CSV)

* [conventional_power_plants_DE.csv](data.open-power-system-data.org/conventional_power_plants/2017-03-03/conventional_power_plants_DE.csv)

* [conventional_power_plants_EU.csv](data.open-power-system-data.org/conventional_power_plants/2017-03-03/conventional_power_plants_EU.csv)