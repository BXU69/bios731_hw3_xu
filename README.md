# BIOS 731 Homework 3: Optimization Algorithms

## Overview

This repository contains Homework 3 for BIOS 731 (Advanced Statistical Computing).
The assignment focuses on optimization methods:

- Newton's method for logistic regression
- MM algorithm for logistic regression
- Comparison of `glm()`, `optim()` (BFGS), Newton, and MM via simulation
- EM algorithm for right-censored exponential survival data

All derivations, code, tables, and figures are included in a single reproducible report.

## Repository Structure

```
bios731_hw3_xu/
├── bios731_hw3_xu.Rproj      # RStudio project file
├── HW_optimization-1.qmd     # Homework questions (qmd file)
├── HW_optimization-2.pdf     # Homework questions (pdf file)
├── hw3_report.Rmd            # Main report source (derivations + code)
├── hw3_report.pdf            # Knitted report output
├── .gitignore                # Ignored local/system files
└── README.md                 # Project overview and reproduction steps
```

## Session Info

```
R version 4.3.2 (2023-10-31)
Platform: aarch64-apple-darwin20 (64-bit)
Running under: macOS 15.6.1

Matrix products: default
BLAS:   /System/Library/Frameworks/Accelerate.framework/Versions/A/Frameworks/vecLib.framework/Versions/A/libBLAS.dylib 
LAPACK: /Library/Frameworks/R.framework/Versions/4.3-arm64/Resources/lib/libRlapack.dylib;  LAPACK version 3.11.0

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

time zone: America/New_York
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] survival_3.5-7 ggplot2_3.5.2 

loaded via a namespace (and not attached):
 [1] vctrs_0.6.5       cli_3.6.4         knitr_1.45        rlang_1.1.5      
 [5] xfun_0.41         generics_0.1.3    labeling_0.4.3    glue_1.8.0       
 [9] colorspace_2.1-1  htmltools_0.5.8.1 scales_1.3.0      fansi_1.0.6      
[13] rmarkdown_2.25    grid_4.3.2        evaluate_0.23     munsell_0.5.0    
[17] tibble_3.2.1      fastmap_1.1.1     yaml_2.3.8        lifecycle_1.0.4  
[21] compiler_4.3.2    dplyr_1.1.4       pkgconfig_2.0.3   rstudioapi_0.15.0
[25] lattice_0.21-9    farver_2.1.1      digest_0.6.37     R6_2.6.1         
[29] tidyselect_1.2.1  utf8_1.2.4        splines_4.3.2     pillar_1.9.0     
[33] magrittr_2.0.3    Matrix_1.6-1.1    withr_3.0.0       tools_4.3.2      
[37] gtable_0.3.4    
```

## Reproduce the Report

1. Clone this repository and open `bios731_hw3_xu.Rproj` in RStudio.
2. Install required packages if needed:
   - `ggplot2`
   - `survival`
   - `knitr`
   - `rmarkdown`
3. Open `hw3_report.Rmd`.
4. Knit to PDF (or run):


