# Del-2-IDR4000

This is a re-analysis of the data from Haun and colleagues studies from 2018 and 2019 [1,2]

## Description 

We aimed to analyze the association between baseline myonuclear density in type-I
and type-II fibres and changes in vastus lateralis fCSA using a linear-mixed effect model (LMM).

## Necessary programs

- R (version 4.5.1)
- Rstudio (version 2026.01.0-392)
- Quarto 

## R-packages

- Tidyverse (v 2.0.0. Use: functions, plotting etc.)
- Exscidata (v. 0.7. Use: Access dataset). The dataset can also be accessed via the Data folder found within the repo
- gt (v. 1.1.0. Use: for creating tables)
- lme4 (v. 1.1-37. Use: modeling LMMs)
- ggeffects (v. 2.3.2. Use: plotting)
- patchwork (v. 1.3.2. Use: plotting)

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
- Clone the repository: `git clone https://github.com/KetilBarstad/Del-2-IDR4000.git`
- Open `Del 2.Rproj` in RStudio
- Install packages in RStudio: `install.packages(c("tidyverse", "lme4", "gt" and so on))`
- If you wish to install exscidata, run: `devtools::install_github("dhammarstrom/exscidata")`
- Open `Del2.qmd` and run the chunks in sequential order to re-produce analysis


## Bibliography

[1] Haun CT, Vann CG, Mobley CB, Osburn SC, Mumford PW, Roberson PA, et al. Pre-training Skeletal Muscle Fiber Size and Predominant Fiber Type Best Predict Hyper-trophic Responses to 6 Weeks of Resistance Training in Previously Trained Young Men.Frontiers in Physiology 2019;10.https://doi.org/10.3389/fphys.2019.00297.

[2] Haun CT, Vann CG, Mobley CB, Roberson PA, Osburn SC, Holmes HM, et al. Effectsof Graded Whey Supplementation During Extreme-Volume Resistance Training. Fron-tiers in Nutrition 2018;5.https://doi.org/10.3389/fnut.2018.00084.
