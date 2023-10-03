# cmi-data
This repository contains the code used to take the raw CMI data from the NBER and prepare it to be used in subsequent analyses. 

* **data** -- I downloaded the CMI data from [the NBER](https://www.nber.org/research/data/centers-medicare-medicaid-services-cms-casemix-file-hospital-ipps). The code uses data from 2006 to 2018. Place these files in "data/input," and create a file "data/output" to house the final dataset. 
* **data-code** -- This folder contains the single code file that extracts the CMI and Medicare Record number from the annual files and combines them into a single dataset. 
