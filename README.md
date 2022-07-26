# Fitzwilliam Museum Collections Data

![A social card for this repository](https://repository-images.githubusercontent.com/511317066/1123904f-cfce-40b2-a3f4-775186e178b3)

[![ORCiD](https://img.shields.io/badge/ORCiD-0000--0002--0246--2335-green.svg)](http://orcid.org/0000-0002-0246-2335)

This repository holds raw data mined from the Museum's collections information systems. These data have been released under CC0 license since around 2010.

Warning - This is a large repository, with a huge number of json and csv files. You will need several GB of disk space to use this data set.

## How are these data generated?

These data were mined from the Museum's Collections API using R scripts.
The API is protected by a bearer token, which can be obtained either
programmatically or via [GUI](https://data.fitzmuseum.cam.ac.uk/api/).
Full documentation of the API can be [found
online](https://data.fitzmuseum.cam.ac.uk/api/v1/docs) and via Postman
collection.

## Data Structure

Data in this repository comes as CSV and JSON, with license and readme in markdown format. To avoid
Github file size limits, images and objects csv files are gzipped. 
Folder structure is as below:

```
|- Root
|- LICENSE.md
|- README.md
|- CITATION.cff
  |- objects-json
     |- *.json - 261,725 files
  |- agents-json  
     |- *.json - 42,308 files
  |- exhibitions-json
     |- *.json - 2,663 files
  |- makers-json
    |- *.json - 6,000 files
  |- periods-json
     |- *.json - 1,582 files
  |- places-json
     |- *.json - 3,726 files
  |- publications-json
     |- *.json - 10,086 files
  |- images-json
     |- *.json - 214,980 files
  |- iiif-json
     |- *.json - 19,846 files
  |- terminology-json
     |- *.json - 129,454 files
  |- ids-csv
    |- object-ids.csv
    |- image-ids.csv
    |- iiif-ids.csv
    |- publications-ids.csv
    |- agents-ids.csv
    |- makers-ids.csv
    |- exhibitions-ids.csv
    |- terminology-ids.csv
    |- periods-ids.csv
    |- places-ids.csv
    |- objects-with-geodata-ids.csv
  |- csv
    |- iiif.csv
    |- departments.csv
    |- images.csv.gz
    |- terminology.csv
    |- objects.csv.gz
    |- publications.csv
    |- exhibitions.csv
    |- places.csv
    |- agents.csv
  |- scripts
    |- rstats
```

## License

Creative Commons Zero 1.0

## Citation

To cite this data repository in APA format: 

Pett, D (2022). The Fitzwilliam Museum Collection MetaData Dump (Version 1.0.0) [Data set]. https://data.fitzmuseum.cam.ac.uk

BIBTEX:

@misc{Daniel_Pett_The_Fitzwilliam_Museum_2022,
author = {Pett, Daniel},
month = {7},
title = {{The Fitzwilliam Museum Collection MetaData Dump}},
url = {https://data.fitzmuseum.cam.ac.uk},
year = {2022}
}

[CITATION.cff](CITATION.cff)
