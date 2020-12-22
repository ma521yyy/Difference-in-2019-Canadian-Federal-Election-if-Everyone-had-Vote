# Overview
This repo contains code and data for identitying the difference for 2019 Canadian Federal Election if "everyone" had voted. It was created by Qiyue Zhang. The purpose is to create a report that summarises the results of a multilevel logistic regression model that we built. Some data is unable to be shared publicly and we detail how to obtain it below. The sections of this repo are: input, output, clean data scripts.

# Accessing Data
Input contain data that are unchanged from their original source. We use two datasets to build our model:

[survey data - To obtain the survey data navigate to "http://www.ces-eec.ca/". The online survey data and documentation can be accessed here: https://doi.org/10.7910/DVN/DUS88V ]

[post-stratification data - To obtain the GSS data, follow the preamble in gss_cleaning-1.R provided by Rohan Alexander and Sam Caetano]

# Clean Data Scripts
Clean data scripts contain R Markdown files that take inputs data then produce selected and cleaned outputs data for further analysis for the paper. These are:

-clean_census_data.Rmd

-clean_survey_data.Rmd

The produced csv data outputs saved in output/~

# Outputs
Output contain data that are cleaned from the input data by clean data scripts, the final report paper in pdf form and its R Markdown file.

-census_cleaned.csv

-survey_cleaned.csv

-paper.pdf

-paper.Rmd