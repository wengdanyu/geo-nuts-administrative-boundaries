Geo Boundaries for NUTS administrative levels 1, 2 and 3 edition 2010.

If you don't know what NUTS (Nomenclature of Territorial Units for Statistics) are, see the [related Wikipedia article](https://en.wikipedia.org/wiki/Nomenclature_of_Territorial_Units_for_Statistics)

## Data

Data is taken from the [GISCO EU website](http://ec.europa.eu/eurostat/web/gisco/geodata/reference-data).

We choose to deliver data as Shapefiles (SHP) and as GeoJSON.

SHP are in `data/shp` directory.

GeoJSON are in `data` folder

Datasets are provided for NUTS levels 1, 2 and 3.

The columns are

* **NUTS_ID**: String (5.0)
* **STAT_LEVL_**: Integer (9.0)

You will also find the original data within `data/NUTS_2010_60M_SH`.

If you need other related informations to NUTS, you can take a look at PDF file describing relationships between original tables in `data/NUTS_2010_60M_SH/NUTS_2010_60M_SH/metadata/NUTS_2010_metadata.pdf`

## Preparation

This package include the script to automate data retrieving and filtering. As we use NodeJs/Io.js, you need to install the software. Then, install dependencies with:

    npm install

To launch all the process, just do `node index.js`.

We choose to let a lot of comments and you may encounter some minors job unrelated code for learning purpose if you need to use [node-gdal library](https://github.com/naturalatlas/node-gdal).

## License

This Data Package is licensed by its maintainers under the [Public Domain Dedication and License (PDDL)](http://opendatacommons.org/licenses/pddl/1.0/).

Refer to the [terms of use](http://www.euribor-rates.eu/disclaimer.asp) of the source dataset for any specific restrictions on using these data in a public or commercial product. You should also be aware that this data comes indirectly from <http://www.emmi-benchmarks.eu/euribor-org/euribor-rates.html>.
Note that underlying rights, terms and conditions in the data from the source are unclear and may exists.