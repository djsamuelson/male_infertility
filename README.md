# male\_infertility data analysis
CodeYou data analysis capstone-project, 2025
## Project by dj samuelson

![Male Infertility](image/male_infertility.png) </br>
Most causes of male infertility are unknown or idopathic.

## About the Project
Aim 1 is to investigate a popular hypothesis that male infertility is associated with poor general health or other health problems.

Aim 2 is to analyze biological data from the visem project to identify molecular signatures of male infertility.

## Running the Program
1. Python 3 is required. This project is written using version 3.13.
2. Clone the repo from github.
3. Setup a virtual environment and activate it.
4. To make sure you have all the necessary packages, run

"pip install -r requirements.txt". 

 The following packages will be required to run the program: 
- pandas, 
- numpy, 
- matplotlib.pyplot, 
- seaborn </br>

5. Use VS Code or Jupyter Notebood to run the "capstone.ipynb" file for this project. </br>

## Project Requirements
Following is a brief description of how data-analysis capstone-project-requirements have been met 

** Environment & Dependendencies
- a virtual environment was used for this project.
- a requirments.txt file is included in the github repo

** Data Ingestion & Cleaning
- local .csv files were used. These data were downloaded from various sources, including the cdc and kaggle.
- EDA was performed on multiple files to determine which databases were a good fit for this project. This EDA work can be found in the "capstone_EDA.ipynb" file. This phase of the projcet yielded three project appropriate and one inappropriate datasets. Two of the appropriate datasets were used in the next phase, which was data analysis and visualization in "capstone.ipynb".

** Feature Engineering & Functions
- new columns were created based on existing data. For example, new columns with human readable descriptions were created from columns containing arbitray categorical data.
- custom functions were used to reclassify existing number-based data into human readable classifications  

** Database Integration
- cleaned data, after EDA, was stored as .csv files and two of these files were used in "capstone.ipynb" for the project
- multiple biological databases were merged based on primary key, ID, to make the "male_fertility_mol_sig.csv" file used in "capstone.ipynb". The merge used pandas and can be found in "capstone_EDA.ipynb".

** Data Visualization
    at least 3 plots each a different type
        all include a title, clearly labeled axes, and unified color themes


## Data Analysis Conclusions 


##data dictionaries

NSFG infertility related data:

../data/2022-2023-NSFG-MalePUFCodebook.pdf contains information for National Survey of Family Growth (NSFG) from the CDC


biological data - molecular signatures

../data/visem\_data\_descriptions.txt contains information for visem molecular signature data







