# Fitzwilliam Museum Collections Data

This repository holds raw data mined from the Museum's collections information systems. These data have been released under CC0 license since around 2010.

Warning - This is a large repository, with a huge number of json and csv files. You will need several GB of disk space to use this data set.

## How are these data generated?

These data are mined from the Museum's Collections API, which is protected by a bearer token authenticated API. These data were mined used R scripts (see scripts directory for examples) and are stored here if you wish to download bulk data.

## Data Structure

Data in this repository comes as CSV and JSON.
```
|- Root
|- LICENSE.md
|- README.md
|- CITATION.cff
  |- objects-json
     |- *.json
  |- agents-json  
     |- *.json
  |- exhibitions-json
     |- *.json
  |- periods-json
     |- *.json
  |- publications-json
     |- *.json
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
  |- scripts
    |- rstats
    |- python
```

## License

Creative Commons Zero 1.0

## Citation

[CITATION.cff](CITATION.cff)
