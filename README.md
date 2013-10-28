BBmisc
======

Miscellaneous helper functions for and from B. Bischl and some other guys at TU Dortmund, mainly for package development.

Offical CRAN release site: 
http://cran.r-project.org/web/packages/BBmisc/index.html

R Documentation in HTML:
http://www.statistik.tu-dortmund.de/~bischl/rdocs/BBmisc/

Installation
============

1) Normal users:
Please use the CRAN version linked above.

2) Early adopters: Simply running
```r
devtools::install_github("BBmisc", username="berndbischl")
```
will install the current github version.

3) Developers and hackers:

You can install a new package version after local code changes if you are in the checkout directory via

devtools::install(".")

Assuming you have a reasonably configured OS and R, you could also build and run tasks via the MAKEFILE.
But only a VERY SMALL percentage of users should be interested in this.

- Clone from git repo here

- Have recent version of R properly installed with all build tools. For Windows this will include 
  
  http://cran.r-project.org/bin/windows/Rtools/

- Have R, Rscript and the binaries of Rtools in your PATH 

- Have roxygen2, devtools and testhat R packages installed

- In a console run "make install" to install. Done.

- "make" will list all other build targets

