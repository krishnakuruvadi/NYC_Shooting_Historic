# NYC_Shooting_Historic

NYPD Shooting Incident Data Report

## Data

Shooting incidents in NYC between 2006 - 2021. 
It can be accessed from https://catalog.data.gov/dataset.

## Intent

* Import data, tidy and model
* Find timings when incidents were reported
* Correlation between race of perpetrator and victim 
* Areas of NYC where incidents were recorded.

## Libraries

Please install these libraries.  The RMD doesnt include installation steps.

* library(tidyverse)
* library(dplyr)
* library(ggplot2)
* library(tidyr)
* library(leaflet)

## Session Info

```
## R version 4.2.2 (2022-10-31)
## Platform: x86_64-apple-darwin17.0 (64-bit)
## Running under: macOS Big Sur ... 10.16
## 
## Matrix products: default
## BLAS:   /Library/Frameworks/R.framework/Versions/4.2/Resources/lib/libRblas.0.dylib
## LAPACK: /Library/Frameworks/R.framework/Versions/4.2/Resources/lib/libRlapack.dylib
## 
## locale:
## [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
##  [1] leaflet_2.1.1   forcats_0.5.2   stringr_1.4.1   dplyr_1.0.10   
##  [5] purrr_0.3.5     readr_2.1.3     tidyr_1.2.1     tibble_3.1.8   
##  [9] ggplot2_3.4.0   tidyverse_1.3.2
## 
## loaded via a namespace (and not attached):
##  [1] lubridate_1.9.0         leaflet.providers_1.9.0 assertthat_0.2.1       
##  [4] digest_0.6.30           utf8_1.2.2              R6_2.5.1               
##  [7] cellranger_1.1.0        backports_1.4.1         reprex_2.0.2           
## [10] evaluate_0.18           highr_0.9               httr_1.4.4             
## [13] pillar_1.8.1            rlang_1.0.6             googlesheets4_1.0.1    
## [16] readxl_1.4.1            rstudioapi_0.14         jquerylib_0.1.4        
## [19] rmarkdown_2.18          labeling_0.4.2          googledrive_2.0.0      
## [22] htmlwidgets_1.5.4       bit_4.0.5               munsell_0.5.0          
## [25] broom_1.0.1             compiler_4.2.2          modelr_0.1.10          
## [28] xfun_0.35               pkgconfig_2.0.3         htmltools_0.5.3        
## [31] tidyselect_1.2.0        fansi_1.0.3             crayon_1.5.2           
## [34] tzdb_0.3.0              dbplyr_2.2.1            withr_2.5.0            
## [37] grid_4.2.2              jsonlite_1.8.3          gtable_0.3.1           
## [40] lifecycle_1.0.3         DBI_1.1.3               magrittr_2.0.3         
## [43] scales_1.2.1            vroom_1.6.0             cli_3.4.1              
## [46] stringi_1.7.8           cachem_1.0.6            farver_2.1.1           
## [49] fs_1.5.2                xml2_1.3.3              bslib_0.4.1            
## [52] ellipsis_0.3.2          generics_0.1.3          vctrs_0.5.1            
## [55] tools_4.2.2             bit64_4.0.5             glue_1.6.2             
## [58] hms_1.1.2               crosstalk_1.2.0         parallel_4.2.2         
## [61] fastmap_1.1.0           yaml_2.3.6              timechange_0.1.1       
## [64] colorspace_2.0-3        gargle_1.2.1            rvest_1.0.3            
## [67] knitr_1.41              haven_2.5.1             sass_0.4.4
```
