# DDoutlier 0.1.0.9001

Renova release, based on CRAN DDoutlier 0.1.0 (archived on CRAN 2025-02-17).

- `man/*.Rd` (COF, DB, INFLO, KDEOS, KNN_AGG, KNN_IN, KNN_SUM, LDF, LDOF, LOCI, LOF, LOOP, NAN, NOF, RDOS, RKOF): deleted the template `\keyword{ ~kwd1 }` and `\keyword{ ~kwd2 }` lines (in `KDEOS.Rd` they were attached to the closing brace of the examples).
- `DESCRIPTION`: `Author` changed from "Jacob H. Madsen <email>" to "Jacob H. Madsen [aut, cre]" and an equivalent `Authors@R` entry was added; `Maintainer` is unchanged (metadata only).
- No R code or `NAMESPACE` change.
- `DESCRIPTION`: `Version` set to `0.1.0.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `LICENSE.md` (full MIT text) was added; the upstream `LICENSE` is unchanged.
- `README.md` was replaced by a short Renova README and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
