# fTree
An R package that implements the methods for growing regression trees with functional output data.

## Package Installation
To install the package open `R` or `Rstudio` and type: `devtools::install_github("ogru/fTree")`. Make sure to have the `devtools` package installed (i.e. `install.packages("devtools")`).

## Tutorial/Vignette
After the installation completes view the package vignette (NOT UPLOADED YET!) to get started: https://rawgit.com/ogru/fTree/master/vignette/fTree_get_started.html

## Troubleshooting

If the package installation fails make sure to update your `R` and `Rstudio` to the latest version(s). 

This code relies on the `Rcpp` and `RcppArmadillo` packages and it compiles Cpp code upon installation. In case of problems, focus your troubleshooting to that domain. 

If installation fails with the following error: "‘to_string’ is not a member of ‘std’", this means that you need to set up your `g++` compiler to use `C++11`. You can accomplish this with the following command (in R/Rstudio): `Sys.setenv("PKG_CXXFLAGS"="-std=c++11")`. Then repeat `devtools::install_github("ogru/fTree")`.

## Contact

Any problems? Raise an issue here on the repo or send me an email ognjengr@gmail.com. 

## Citation

If you find this sofware useful please consider citing it in your publications. You may use the following bibtex type citation entry:
```
@Manual{fTree_2017,
  title  = {fTree, an \proglang{R} package},
  author = {Ognjen Grujic},
  year   = {2017},
  note   = {\proglang{R}~package version~1.0},
  url    = {https://github.com/ogru/fTree},
}
```

