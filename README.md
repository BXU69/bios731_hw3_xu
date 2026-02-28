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

loaded via a namespace (and not attached):
 [1] compiler_4.3.2    fastmap_1.1.1     cli_3.6.4         htmltools_0.5.8.1
 [5] tools_4.3.2       rstudioapi_0.15.0 yaml_2.3.8        rmarkdown_2.25   
 [9] knitr_1.45        xfun_0.41         digest_0.6.37     rlang_1.1.5      
[13] evaluate_0.23    
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


