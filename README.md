# input data generation for material flow analysis models

R package **mrmaterials**, version **0.0.2**

[![CRAN status](https://www.r-pkg.org/badges/version/mrmaterials)](https://cran.r-project.org/package=mrmaterials)  [![R build status](https://github.com/pik-piam/mrmaterials/workflows/check/badge.svg)](https://github.com/pik-piam/mrmaterials/actions) [![codecov](https://codecov.io/gh/pik-piam/mrmaterials/branch/master/graph/badge.svg)](https://app.codecov.io/gh/pik-piam/mrmaterials) 

## Purpose and Functionality

Input data generation for material flow analysis models using the madrat framework.


## Installation

For installation of the most recent package version an additional repository has to be added in R:

```r
options(repos = c(CRAN = "@CRAN@", pik = "https://rse.pik-potsdam.de/r/packages"))
```
The additional repository can be made available permanently by adding the line above to a file called `.Rprofile` stored in the home folder of your system (`Sys.glob("~")` in R returns the home directory).

After that the most recent version of the package can be installed using `install.packages`:

```r 
install.packages("mrmaterials")
```

Package updates can be installed using `update.packages` (make sure that the additional repository has been added before running that command):

```r 
update.packages()
```

## Questions / Problems

In case of questions / problems please contact Falk Benke <benke@pik-potsdam.de>.

## Citation

To cite package **mrmaterials** in publications use:

Benke F, Dürrwächter J (2024). _mrmaterials: input data generation for material flow analysis models_. R package version 0.0.2, <https://github.com/pik-piam/mrmaterials>.

A BibTeX entry for LaTeX users is

 ```latex
@Manual{,
  title = {mrmaterials: input data generation for material flow analysis models},
  author = {Falk Benke and Jakob Dürrwächter},
  year = {2024},
  note = {R package version 0.0.2},
  url = {https://github.com/pik-piam/mrmaterials},
}
```
