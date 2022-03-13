Average rainfall in Melbourne and Oxford  
====

This repository contains an analysis of the monthly average rainfall in Melbourne and Oxford between 1855-2015.

To run this analysis, the two data frames were first combined using the following command:

```
Rscript src/combine-data.R
```
The results were then generated using the following command: 
```
Rscript src/make-plot.R
```

The initial input data and the combined data frame are in `data` and the results are in `out`.

DATA
====

Melbourne climate statistics
----------------------------

The data was obtained from the Bureau of Meteorology:

http://www.bom.gov.au/climate/averages/tables/cw_086071.shtml

Oxford climate statistics
-------------------------

The data was obtained from the Met Office:

https://www.metoffice.gov.uk/pub/data/weather/uk/climate/stationdata/oxforddata.txt
