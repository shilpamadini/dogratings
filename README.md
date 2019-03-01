# dogratings

This project explores  the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.
Various steps of Data Wrangling prcess data gathering, assessing, and cleaning and then Analysis is performed and explained through visualization

## Contents

1. act_report.ipynb
    * Jupyter notebook file to run the data analysis and visualization on cleaned data set.
2. wrangle_act.ipynb
    * Jupyter notebook file to capturing the entire data wrangling process.
3. reports
    * act_report.html
       * final report for data analysis and visualization
    * wrangle_act.html
       * final report for data wrangling steps
4. source data
    * image-predictions.tsv
    * tweet_json.txt
    * tweet_archive_enhanced.csv
5. cleaned data sets
    * tweet_archive_data_clean.csv
    * tweet_count_data_clean.csv
    * tweet_image_data_clean.csv
6. twitter_archive_master.csv
    * final master file that consists of dataset ready for analysis
7. README.md
8. environment.yaml
    * environment file for this project

## Installation
please follow below instruction to create this project environment on your local desktop.
- download the project folder from the github url
     ```
    git clone https://github.com/shilpamadini/dogratings.git
    ```
- install the conda environment using the environment file. this will create a conda environment with the same name listed in the environment file. this will also install all the required packages for this project
    ```
    conda env create -f environment.yaml
    ```
- list the conda environments
     ```
     conda env list
     ```
- activate the enviroment for bikeshare
     ```
     source activate dand_py3
     ```

## Functionality

The wrangle_act.ipynb file consists of the steps to gather dog ratings tweets data set from various data sources
programmatically. After the data is gathered, it is assessed for quality and tidiness. Series of data cleansing steps are performed to address quality issues and prepare a cleaned data set for analysis. Once the final set is ready it is exported into a master file for storing.

act_report.ipynb consits of steps to perform data analysis and visualization on the master data set.
