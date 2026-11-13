# DDoutlier

Distance- and density-based outlier detection algorithms (LOF, COF, INFLO, KDEOS, LOOP, LOCI and others) for multidimensional data.

Compatibility updates by Renova.

Version 0.1.0.9001 removes the template `\keyword{ ~kwd1 }` and `\keyword{ ~kwd2 }` placeholders from 16 help pages and adds an `Authors@R` entry equivalent to the existing author and maintainer. No R function was changed.

## Install

```r
install.packages("DDoutlier", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/DDoutlier@renova-0.1.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

DDoutlier is by Jacob H. Madsen (maintainer); the original project is at <https://github.com/jhmadsen/DDoutlier>. License: MIT + file LICENSE; see [LICENSE](LICENSE) (Copyright 2018 Jacob H. Madsen) and [LICENSE.md](LICENSE.md) (full MIT text).
