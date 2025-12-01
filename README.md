# Advanced Data Analysis Final Project: 
The Influence of Health Insurance Type on Emergency Room Utilization Among U.S. Adults Aged 65 and Older (2023)


## Project Description
This project analyzes data from the 2023 National Health Interview Survey (NHIS) to examine factors, particularly insurance type, associated 
with emergency room utilization among older adults. The repository includes raw data, cleaning and recoding files, processed analytic datasets, 
and R Markdown code used to conduct descriptive analyses, assess model assumptions, and run an ordinal logistic regression.


## Folder Structure, Files Included, What They Do
README.md: This file

Raw Data Folder:
  - adult23.csv: Original NHIS 2023 adult dataset.
  - CleaningRecoding.Rmd: R Markdown script that reads original dataset, recodes variables, cleans data, generates figure 1, & creates 
                          final analytic sample 
                          
Processed Data Folder: 
  - nhis2023_completeCCA.csv: Cleaned and fully processed dataset produced from CleaningRecoding.Rmd, to use for analysis
  - AnalysisCode.Rmd: R Markdown script used for running descriptive statistics, checking assumptions, running multivariable ordinal 
                       logistic regression model, and exporting model outputs and tables
                       

## How to Run the Code
1. Download or clone this repository to your computer
2. Open `analysis_code.Rmd` in RStudio
3. Make sure your working directory is set to the folder where the files are
saved
4. Run the script

*Note all plots/images can be copied/exported by knitting to an HTML and opening in browser and copying; some (ex. descriptive plot) will be saved to directory 
where file lives



## Author / Date
- Name: Katie Lawler
- Course: Advanced Data Analysis
- Date: December 2025 Y


Citations:
- All key sources can be found in FP4 Assignment
- ChatGBT was used to help format code, debug, etc.

