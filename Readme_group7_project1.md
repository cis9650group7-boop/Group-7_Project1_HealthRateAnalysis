## Project 1: Analysis of Health Rate

### Author: CIS 9650 Group 7 (Anish Bijusoman, Ivana Sundararao, Qingrong Tan, Reem Hussein)
### Date: November 28th, 2025


### Project Link
https://github.com/cis9650group7-boop/Group-7_Project1_HealthRateAnalysis

Include:
1. term_project_group7.ipynb
2. Readme_group7_project1.md
3. CIS 9650 - Meetings Notes - Group 7.pdf


### Dataset
https://storage.googleapis.com/msba-online-data/CIS9650/Project%2001/healthrate.ratemd.ny.csv


### How to run
This project can be executed either on Google Colab or on a local machine.

Option 1 - Run on Google Colab
1. Open term_project_group7.ipynb in Google Colab.
2. Run all cells in order. The notebook will load the dataset from Google Cloud Storage. No additional setup is required.

Option 2 - Run Locally
1. Download the following files and place them in the same directory on your computer:
   
   term_project_group7.ipynb
   
   healthrate.ratemd.ny.csv
   
3. Open term_project_group7.ipynb in Jupyter Notebook
4. Run all cells in order. The notebook will first attempt to load the dataset from Google Cloud Storage. If the cloud dataset cannot be accessed, the notebook will automatically use the local dataset instead.


### Project Overview
This project uses the healthrate.ratemd.ny.csv dataset to load doctor ratings and patient comments across New York State. The goal of this project is to understand what drives variation in doctor ratings across medical providers in New York State. Our analysis includes (1) specialty-level rating variation, (2) the relationship between helpfulness and overall rating, (3) the relative impact of sub-ratings on overall satisfaction, and (4) how location and facility characteristics influence patient experience.


### Notebook Structure
1. Introduction
2. Problem Statement / Research Question
3. Data Description
4. Setup and Environment
5. Data Loading
6. Data Preparation
7. Modeling and Analysis
   
   Analysis 1: Specialty-Level Rating Variation and Insights from Patient Feedback
   
   Analysis 2: Correlation between Helpfulness and Overall Rating
   
   Analysis 3: Relative Impact of Sub Ratings on Overall Doctor Rating
   
   Analysis 4: Location Ratings and Facility Impact on Patient Satisfaction
9. Conclusion
10. References


