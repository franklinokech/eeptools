## Test environments
* local Windows 11 install, R 4.3.0
* r-hub: "ubuntu-gcc-devel", "windows-x86_64-devel", "debian-gcc-release"

## Previous Issues with Test Errors have Been Resolved

## R CMD check results
There were no ERRORs or WARNINGs or NOTEs. 

There is one NOTE:
* Used utils::globalVariables(c(".fitted", ".resid",".stdresid",".cooksd",
"rows",".hat")) to fix notes about unexported objects in `autoplot.lm`
* Used utils::globalVariables(c("moves", "switches", ".SD")) to fix notes about 
unexported objects in `moves_calc`
* Used utils::globalVariables(c("adv", "grade", "count", "id", "gradeP", 
"vals", "prof")) to fix notes about unexported objects in `profpoly`


## Downstream dependencies
There are no downstream dependencies.