# Armenian online job postings Wrangling Operations

## By Vidhyut Prajapati

# Introduction

This project focused on wrangling data from the Armenian online job postings using Python, documented in a Jupyter Notebook. This Dataset rates online jobs with humorous commentary. The dataset has more than 19000 rows with 24 columns of data with different attributes. The project is builiding to create interesting and trustworthy analyses and visualizations.


# Key Points
Key points to keep in mind when data wrangling for this project:

- We only need to do is nondescriptive and misspelled column headers (ApplicationP, AboutC, RequiredQual, JobRequirment) and replace them with full words (ApplicationProcedure, AboutCompany, RequiredQualifications, JobRequirement)

- Select all records in the StartDate column that have "As soon as possible", "Immediately", etc. and replace the text in those cells with "ASAP"

- Make a copy of cleaned Dataset


# Project Details
Fully assessing and cleaning the entire dataset would require exceptional effort so only a subset of its issues (eight quality issues and two tidiness issues at minimum) needed to be assessed and cleaned.

The tasks for this project were:

- Data wrangling, which consists of:
  - Gathering data
  - Assessing data
  - Cleaning data
- Storing, analyzing, and visualizing our wrangled data
Reporting on
  - our data wrangling efforts and
  - our data analyses and visualizations

## Installing
- Install Jupyter Notebook to run wrangle_act.ipynb.

- Require the following libraries installed.

- numpy

- pandas

- requests


- matplotlib.pyplot

## Files
- 1844_3192_bundle_archive.zip: Zip file of dataset.
- features.txt: text file with all the information about attributes.
- online-job-postings.csv : csv file which is used in data wrangling act


## Resources
- Files downloaded from Udacity
- Google.com
- Stackoverflow.com
