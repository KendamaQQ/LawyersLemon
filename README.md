This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This RTutor problem set renders possible to replicate the main findings in "Is your Lawyer a Lemon? Incentives and Selection in the Public Provision of Criminal Defense" by Amanda Agan, Matthew Freedman and Emily Owens.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("KendamaQQ/RTutorLawyers", upgrade_dependencies=FALSE)
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorLawyers)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorLawyers")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorLawyers",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
