# gdejong_gca_with_dominance_models

This git repository contains the code used to evaluate the performance of different genomic prediction models to predict GCA and select parents in the early stage of a hybrid breeding program. The code is provided for reproducibility and further research and complements the following paper

```
@article{Jong2023Comparison,
  author = {de Jong, G and Powell, O and Gorjanc, G and Hickey, J M and Gaynor, R C},
  title = {Comparison of genomic prediction models for general combining ability in early
           stages of hybrid breeding programs},
  journal = {Crop Science},
  year = {2023},
  url = {https://doi.org/10.1002/csc2.21105}
}
```

The code was run with R 4.6.1 and AlphaSimR 1.10.0.

To run the code: 
  1) Run `BURNIN.R`
  2) In the DH Rapid Cycle folder, run `GSDH.Model*_*.R` -- select the model and scenario desired.

Results folder: contains the results of 100 runs for each model and scenario.
