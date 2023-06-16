# Risk Analysis of Australia's Higher Education Loan Program (HELP)

## Project Description

This project examines the total value, growth, demographic distribution and risks associated with the Australian Government's Higher Education Loan Program (HELP) over the period 2005-2022.

## Data

This folder contains the .xlsx and .csv data files.

In this folder:

- help-statistics-2021-2022.xlsx: The .xlsx data set of HELP statistics retrieved from [Data.gov.au](https://data.gov.au/dataset/ds-dga-ce4c58ec-c930-4a05-8a37-f244d960e5f8/details?q=taxation%20statistics)
- HELP_DATA_TIDIED.csv: The tidied .csv data table from Table 8 of the original data set

## Requirements

This project has been built on R ver 4.3.0 (April 2023) and may be incompatible with different versions. 
If you encounter issues, download R 4.3.0 from [CRAN](https://cran.r-project.org/).

Some of the R packages and versions required for this reproduction of this project:

- bookdown [0.34]
- dplyr [1.1.2]
- eeptools [ 1.2.5]
- ggplot2 [3.4.2]
- gridExtra [2.3]
- knitr [1.42]
- readxl [1.4.2]
- scales [1.2.1]
- tidyr [1.3.0]
- tidyverse [2.0.0]

For the full list of packages and versions used to build this project, see the packages file. 

## How to install and run

- When installing the project for the first time, call renv::restore() and enter Y when prompted to install the packages required.
- If download errors occur:
    - run options("download.file.method"="libcurl") to ensure the method is "libcurl"
    - then run RENV_DOWNLOAD_FILE_METHOD = "libcurl"
- The html report can be reproduced by knitting the project from the HELP_Analysis.Rmd file.
- If prompted, accept and install any new dependencies.

## Credits

This report has been prepared by Alana Dabelstein, Anh-Thu Hoang, and Chenxi Zhang for ETO5513.

## License

This report is available under Creative Commons Zero v1.0 Universal. See the LICENSE file for more info.
