## Test environments
* local Ubuntu 18.04 install, R 3.6.1
* R-devel on Windows Server 2008 R2 SP1, 32/64 bit, with `rhub::check()`
* Debian 8, R 3.5.3

## R CMD check results
There were no ERRORS, WARNINGS, or NOTES

## Downstream dependencies
Ran `revdepcheck::revdep_check()` with no ERRORs, WARNINGS, or NOTEs.
The only dependent package is `rpostgisLT`, which is also maintained by the `rpostgis` group.

## Notes
Note that due to the requirement of a PostgreSQL/PostGIS enabled database for functions in this package, 
all package tests are run locally and excluded from the R build.