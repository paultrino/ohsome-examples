# OHSOME EXAMPLES
Ohsome is an API for accessing historical data from Open Street Maps (OSM)

OSM's data has metadata defining when the feature was added. Ohsome API allows us to query for features listed at specific dates (e.g. 2015). 

## Get Started (conda/mamba)

This project was slightly modified from the original, with the addition of a `environments.yml` file in the project base for conda/mamba workflows. 

1) Open a terminal window
2) Invoke a  `conda env create -f environments.yml` to create a conda VM
3) Invoke a `jupyter lab`, you should see the server print output to the screen.
4) Click on the link in the output that says where your server is running.

# ORIGINAL README...
This Repository contains a collection of examples of how to work with the [ohsome API](https://api.ohsome.org).

## Python examples

The [`Python`](https://github.com/GIScience/ohsome-examples/tree/master/python#readme) directory contains the following examples written in Python using jupyter notebooks:

* [Data Aggregation Endpoint](https://nbviewer.jupyter.org/github/GIScience/ohsome-examples/blob/master/python/jupyter-notebooks/ohsome-data-aggregation.ipynb)
* [Analysing HOT Tasking Manager Projects in Nepal](https://nbviewer.jupyter.org/github/GIScience/ohsome-examples/blob/master/python/jupyter-notebooks/ohsome_api_hot_tm_project1008.ipynb)
* [Complex analysis with the magical filter parameter](https://nbviewer.jupyter.org/github/GIScience/ohsome-examples/blob/master/python/jupyter-notebooks/cycling-magic-filter-ohsomeAPI.ipynb)

## R examples

The [`R`](https://github.com/GIScience/ohsome-examples/tree/master/R#readme) directory contains the following examples written in R:

* [How to use the ohsome API with R](https://github.com/GIScience/ohsome-examples/tree/master/R/ohsome-api-requests#readme)

## Further examples

You can find further usage examples of the ohsome API in the following places:

* [ohsome-api-analysis-examples](https://gitlab.gistools.geog.uni-heidelberg.de/giscience/big-data/ohsome/ohsome-api-analysis-examples) – a collection of further examples of analyses using the ohsome API.
  * [Exploring Localness](https://gitlab.gistools.geog.uni-heidelberg.de/giscience/big-data/ohsome/ohsome-api-analysis-examples/exploring-localness-blogpost) [Blogpost](http://k1z.blog.uni-heidelberg.de/2020/11/23/exploring-localness-of-osm-data-an-analysis-using-the-oshdb-and-ohsome-api/).
* the whole [how to become ohsome](http://k1z.blog.uni-heidelberg.de/tag/become-ohsome/) series on the giscience blog.
* [visualizing the evolution of OSM data using QGIS](https://gitlab.gistools.geog.uni-heidelberg.de/-/snippets/23)

## Contributing

Please read our [contributing guide](https://github.com/GIScience/ohsome-examples/tree/master/CONTRIBUTING.md) if you're interested in helping to improve this repository.
