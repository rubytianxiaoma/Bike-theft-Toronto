# Overview
This repo contains code and data for the paper,"Toronto Bike Thieves in Action: What Is Their Favorite Bicycle?". It was created by Tianxiao Ma and Yu-Chun Chien. The paper aims to discover the most common characteristics of those stolen bikes in bike thefts from 2014 to 2019 occured in City of Toronto. 

Three sections contained in this repo: Support dataset, R code, and output. Details about references can be found in either R code folder and Paper folder.

- Support dataset folder contains all the dataset used in the paper.
  - *Bicycle_Data_Code_Sheet.pdf* is the cheat sheet of some initials used in the analyzed dataset *bicycle-thefts-2014-2019.csv*.
  
  - *Bicycle_Thefts_Metadata.csv* is the metadata of the main analyzed dataset *bicycle-thefts-2014-2019.csv*. 
  
  - *bicycle-thefts-2014-2019.csv* is the analyzed dataset issued by Toronto Police Service Public Safety Data Portal. Retrived from https://data.torontopolice.on.ca/datasets/bicycle-thefts.The original dataset contains 21,584 recorded bike thefts that took place in the City of Toronto from 2014 to 2019 with corresponding information. The version of the data is updated by Toronto Police service public safety data portal over time. In the paper, we used the dataset contains Bicycle Thefts occurrences from 2014-2019. 
  
  - *neighbourhood_shapefile.Rds* Contains the 2016 Neighbourhood Profiles are based on data collected by Statistics Canada in its 2016 Census of Population.Retrived from www.toronto.ca/open. In this paper, we use this file to draw maps of city of Toronto.

  
- R code folder contains all the code needed for building the report:
  - *Bike-theft.Rmd* contains code build for the paper. Corresponding pdf version of the paper can be found in the repo locates at /Paper/Bike-theft.pdf


- Paper folder contains the pdf version of the report. Corresponding code script can be found in R code folder.
  - *Bike-theft.pdf*