# Characterizing the US Research Computing and Data (RCD) Workforce Analysis

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MiddelkoopT/CaRCC-RCD-Census-Paper-PEARC22-data.git/HEAD)

Data sets to accompany "Characterizing the US Research Computing and Data (RCD) Workforce"

Dataset citation: Maimone, Christina, Yockel, Scott, Alameda, Jay, Middelkoop, Timothy, Neeser, Amy, & Stauffer, Ashley. (2022). CaRCC Research Computing and Data (RCD) Workforce Survey Data 2021 - Part 1 (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.6574465

Paper citation: Christina Maimone, Scott Yockel, Timothy Middelkoop, Ashley Stauffer, and Chris Reidy. 2022. Characterizing the US Research
Computing and Data (RCD) Workforce. In Practice and Experience in Advanced Research Computing (PEARC ’22), July 10–14, 2022,
Boston, MA, USA. ACM, New York, NY, USA, 12 pages. https://doi.org/10.1145/3491418.3530289

Survey questions citation: Maimone, Christina, Yockel, Scott, Middelkoop, Timothy, Alameda, Jay, Stauffer, Ashley, & Neeser, Amy. (2021). CaRCC Research Computing and Data (RCD) Workforce 2021 Census Questions (1.0). Zenodo. https://doi.org/10.5281/zenodo.5914431

Notes:

The datasets are split and the set of variables is restricted to protect the privacy of survey respondents.  While identifying information is not included here, the broader set of survey answers did include information that could be used to identify individuals.  

public_analysis.Rmd includes R code to compute the values reported in the paper using the datasets shared here.  

codebook_shared.xlsx contains a list of all of the variables included across data files, as well as a mapping of the variables to the individual datasets.  

For some datasets, individual responses are shared; in these data sets, variables are each a column.  The rows in all datasets showing individual responses have been randomized.  These data sets cannot be joined together.

In the other datasets, only the frequency of each combination of responses is shared; in these datasets, the variable is denoted in a "variable" column and the response to that variable is in the "category" column.  

gender_counts.csv: Only respondents who chose Male or Female for gender are included because the other groups are too small to include breakouts by the answers to other questions.  Only includes those with current RCD employment.

ethnicity_counts.csv: Respondents are divided into White (alone or with another identity) and Not White because breaking down additional individual race and ethnic groups by the answers to other questions results in subgroups that are too small to share.  Only includes those with current RCD employment.

inclusion.csv: This file is in a wide format instead of a long format like the other frequency datasets.  

Contact for questions or more information: Christina Maimone