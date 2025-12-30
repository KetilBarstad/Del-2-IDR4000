# Del-2-IDR4000

This is a re-analysis of the data from Haun and colleagues studies from 2018 and 2019

## Description 

We aimed to analyze the association between baseline myonuclear density in type-I
and type-II fibres and changes in vastus lateralis fCSA using a linear-mixed effect model (LMM).
## Necessary programs

- R (version 4.5.1)
- Rstudio (version 2025.09.2)
- Quarto 

## R-packages

- Tidyverse (functions, plotting etc.)
- Exscidata (dataset)
- gt (for creating tables)
- lme4 (modeling LMMs)

## Folder structure

```
Del2/
├── Data/           # Raw data files from Haun et al.
├── Del2.qmd        # Main Quarto document with R code
├── Del2.pdf        # Rendered PDF output
├── Del 2.Rproj     # RStudio project file
├── references.bib  # Bibliography
├── vancouver.csl   # Citation style
└── README.md
```

## How to reproduce analysis

- Install packages in RStudio: `install.packages(c("tidyverse", "lme4", "gt"))`
- Clone the repository: `git clone https://github.com/YourUsername/Del2.git`
- Open `Del 2.Rproj` in RStudio
- Open Rstudio, and load the packages: `library(tidyverse), library(lme4), and so on`
- Open `Del2.qmd` and run the chunks in sequential order to re-produce analysis


## Bibliography

Haun CT, Vann CG, Mobley CB, Roberson PA, Osburn SC, Holmes HM, et al. Effectsof Graded Whey Supplementation During Extreme-Volume Resistance Training. Fron-tiers in Nutrition 2018;5.https://doi.org/10.3389/fnut.2018.00084.12

Haun CT, Vann CG, Mobley CB, Osburn SC, Mumford PW, Roberson PA, et al. Pre-training Skeletal Muscle Fiber Size and Predominant Fiber Type Best Predict Hyper-trophic Responses to 6 Weeks of Resistance Training in Previously Trained Young Men.Frontiers in Physiology 2019;10.https://doi.org/10.3389/fphys.2019.00297.