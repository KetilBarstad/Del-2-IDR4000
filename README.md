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

Del2/
├── Data/
│   └── [raw data files containing the hypertrophy dataset]
├── Del2.qmd
├── Del2.pdf
├── Del 2.Rproj
├── references.bib  #Bibliography
├── vancouver.csl   #Citation style
└── README.md

## How to perform statistical analysis 

1. Clone this repository.
2. Open the R-project in R-studio. 
3. Install required packages.
4. Render the Quarto document: 'quarto render Del2.qmd'


## Bibliography

- Haun CT et al. (2018). Effects of Graded Whey Supplementation During Extreme-Volume Resistance Training. *Front Nutr.*
- Haun CT et al. (2019). Pre-training Skeletal Muscle Fiber Size and Predominant Fiber Type Best Predict Hypertrophic Responses. *Front Physiol.*