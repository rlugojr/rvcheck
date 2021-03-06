rvcheck: Check R/Package Version
---------

[![CRAN_Status_Badge](http://www.r-pkg.org/badges/version/rvcheck?color=green)](https://cran.r-project.org/package=rvcheck)
![](https://cranlogs.r-pkg.org/badges/grand-total/rvcheck?color=green)
![](https://cranlogs.r-pkg.org/badges/rvcheck?color=green)
![](https://cranlogs.r-pkg.org/badges/last-week/rvcheck?color=green)
[![gitter](https://img.shields.io/badge/GITTER-join%20chat-green.svg)](https://gitter.im/GuangchuangYu/Bioinformatics)


## Authors ##

Guangchuang YU <https://guangchuangyu.github.io>

School of Public Health, The University of Hong Kong 

## Installation ##

Get the released version from CRAN:

```r
install.packages("rvcheck")
```

Or the development version from github:

```r
## install.packages("devtools")
devtools::install_github("GuangchuangYu/rvcheck")
```

## Examples ##

```r
library(rvcheck)
check_r()
check_bioc('ggtree')
check_cran('emojifont')
check_github("guangchuangyu/clusterProfiler")
```
