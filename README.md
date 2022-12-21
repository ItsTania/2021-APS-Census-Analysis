# 2021-APS-Census-Analysis
The final independent project for the Data for Decision Making (SOCR3001) course. 

## [Table of Contents](#table-of-contents)
1. [About](#about)
2. [Usage](#usage)
3. [Project Organization](#project-organization)

## [About](#about)
This report was primarily influenced by the release of the 'Delivering for Tomorrow: APS Workforce Strategy 2025'. 
As this was a short report, it focuses on the early career category. 
While the analysis itself if not complex, this project highlights the role data can play in public policy.

### Data Source:
This project surrounded the 2021 APS census data. It contained the aggragated the outcomes the APS' workforce satisfaction survey. 

https://www.apsc.gov.au/initiatives-and-programs/workforce-information/aps-employee-census-2021
https://data.gov.au/data/dataset/3b90a6bf-d195-4692-83c6-ef874dca5593/resource/80a7aa04-87f6-4d42-8d52-6cb51fd84918/download/2021-aps-employee-census-5-point-dataset.csv

## [Notebooks](#notebooks)
1. `01_data_analysis.Rmd` 
   - Summary of the relevant data analysis and methods used to generate the figures
2. `02_final_report.ipynb` 
   - The document used to knit the final report

## [Project Organization](#project-organization)

    ├── .gitignore                    <- files and folders to be ignored by version control system
    ├── README.md                     <- The top-level README for developers using this project.
    ├── data                          <- Data and instructions on how to download them
    ├── figures                       <- Generated graphics and figures to be used in reporting
    └── *.Rmd                       <- R markdown notebooks. Naming convention is a number (for ordering),
                                         and a short `-` delimited description, e.g. `1.0-jqp-initial-data-exploration`.

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
