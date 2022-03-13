This repository contains an analysis of the monthly average rainfall in Melbourne and Oxford between 1855-2015.

To run this analysis, the two data frames were first combined using the following command:

```
Rscript src/combine-data.R
```
The results were then generated using the following command: 
```
Rscript src/make-plot.R
```

The initial input data and the combined dataframe are in `data` and the results are in `out`.
