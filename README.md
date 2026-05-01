# AI Semiconductor Ecosystem
An interactive visualization project exploring the global AI semiconductor ecosystem.

**Website**  
https://shanjiang08.github.io/AI_Semiconductor_Project/

**Overview**  
With the rapid development of artificial intelligence, the demand for computational power continues to grow. As a result, semiconductors have become an essential foundation supporting modern AI systems. This project aims to provide a more comprehensive understanding of the semiconductor ecosystem from multiple perspectives, including raw materials, semiconductor manufacturing, trade interventions, chip price trends, and investment patterns.

**Project Scope**  
The project covers raw material production and distribution, semiconductor manufacturing stages with dominant suppliers, semiconductor trade interventions, chip price trends across key AI milestones, country-level investment in semiconductor manufacturing, company-level comparison of R&D and capital expenditure, and the relationship between investment intensity and profitability.

**Methods**  
This project combines data cleaning, abstraction, and visualization to analyze the structure of the semiconductor industry. Interactive charts are used to support comparison across countries, companies, and time periods.

The visualizations include pie charts, bar charts, stacked bar charts, line charts, and scatter plots. Interactive features include filtering, highlighting, and coordinated views across multiple charts.

**Data Sources**  
| # | Source | License | Update Frequency | URL |
|---|--------|---------|-----------------|-----|
| 1 | USGS – Silicon Statistics and Information (myb1-2023-simet-ERT_0.xlsx, T8) | CC0 1.0 | Not specified | https://www.usgs.gov/centers/national-minerals-information-center/silicon-statistics-and-information |
| 2 | USGS – Germanium Statistics and Information (myb1-2023-germanium.xlsx, T1) | CC0 1.0 | Not specified | https://www.usgs.gov/centers/national-minerals-information-center/germanium-statistics-and-information |
| 3 | USGS – Gallium Statistics and Information (myb1-2023-galli-ERT.xlsx, T7) | CC0 1.0 | Not specified | https://www.usgs.gov/centers/national-minerals-information-center/gallium-statistics-and-information |
| 4 | USGS – Arsenic Statistics and Information (myb1-2023-arsen-ert.xlsx, T3) | CC0 1.0 | Not specified | https://www.usgs.gov/centers/national-minerals-information-center/arsenic-statistics-and-information |
| 5 | USGS – Mineral Commodity Summaries 2025 Data Release (mcs2025-simet_salient.csv, mcs2025-germa_salient.csv, mcs2025-galli_salient.csv, mcs2025-arsen_salient.csv) | CC0 1.0 | Annual | https://www.sciencebase.gov/catalog/item/6793e234d34e72688d6b71e7 |
| 6 | Emerging Technology Observatory – Advanced Semiconductor Supply Chain / ChipExplorer (inputs.csv, providers.csv, provision.csv, sequence.csv, stages.csv) | CC BY-NC 4.0 | Annual | https://eto.tech/dataset-docs/chipexplorer/ |
| 7 | Global Trade Alert – Export Controls on Semiconductors | CC BY 4.0 | Continuous | https://globaltradealert.org/threads/export-controls-on-semiconductors |
| 8 | FRED – Producer Price Index by Industry: Semiconductor and Other Electronic Component Manufacturing (PCU33443344) | Public domain | Monthly | https://fred.stlouisfed.org/series/PCU33443344 |
| 9 | OECD – Analytical Business Enterprise R&D by ISIC Rev.4 Industry (ANBERD, C26/C261, 2018–2022) | CC BY 4.0 | Updated November 28, 2024 | https://data-explorer.oecd.org/vis?tm=ANBERD&pg=0&snb=1&df[ds]=dsDisseminateFinalDMZ&df[id]=DSD_ANBERD%40DF_ANBERDi4&df[ag]=OECD.STI.STP&df[vs]=1.0&dq=TWN%2BFRA%2BDEU%2BJPN%2BKOR%2BGBR%2BUSA%2BCHN.A..C26%2BC261.XDC.V.&pd=2018%2C2022&to[TIME_PERIOD]=false |
| 10 | European Commission – The 2025 EU Industrial R&D Investment Scoreboard – World 2000 (SB2025_World2000_2.xlsx) | CC BY 4.0 | Annual | https://iri.jrc.ec.europa.eu/scoreboard/2025-eu-industrial-rd-investment-scoreboard#field_data |

**Tech Stack**  
Python (Pandas), Altair, HTML, CSS, JavaScript, and GitHub Pages.

**Limitations**  
This project has certain limitations related to data and analytical methods. Certain dataset timelines are inconsistent, and datasets are collected from various institutions, which may affect direct comparison and analysis results. In addition, this project focuses mainly on descriptive analysis and lacks more in-depth quantitative analytical methods.

**Future Work**  
In the future, this project can integrate more unified and updated data sources to enhance comparability across variables. It can also further adopt machine learning methods to analyze relationships among key variables.

**Author**  
Shan Jiang  
Department of Computer Science  
University of British Columbia  

**Supervisor**  
Oluwakemi Ola  
Department of Computer Science  
University of British Columbia
