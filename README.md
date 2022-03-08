# github-assignment

This repository contains an analysis of changes in rainfall in Oxford and Melborne from 1955 to 2015 in the months of February to December.

To run this analysis, you need to use two scripts. The first script combines data from Oxford and Melborne and the second script can run the plot to visualise changes in average rainfall. These two R scripts can be found using the following command:

```
Rscript src/combine.data.R
Rscript src/make-plot.R
```

The input data for the combine.data.R script are in `data`
The input data for the make-plot.R script are in `out` as it is the output of the combine.data.R script
and the results of make-plot.R are in `out`.
The output data on regression summary and package versions for both scripts are in `out`

