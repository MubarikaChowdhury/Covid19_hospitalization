---
title: "Analysing the COVID-19 Delta Variant Data"
author: "Sultana Mubarika Rahman Chowdhury"
date: '2022-07-29'
---
  

## Introduction
The aim of this project was to apply the skills learned in Advanced R programming class in wrangling, cleaning, and extracting information from the CDC's [open data repository](https://healthdata.gov/Health/COVID-19-Community-Profile-Report/gqxm-d9w9) related to the Delta variant of COVID-19 hospitalization tren for three Florida Counties namely Miami-Dade, Palm Beach, and  Broward.


## Our Processs
In order to replicate this work, here are the following steps:

1. Go to <https://healthdata.gov/Health/COVID-19-Community-Profile-Report/gqxm-d9w9> and download the `.xlsx` files for the dates of interest. We check for new data files daily. 

2. Save the selected data files to `data_CDC_raw/` (do not change the file names; they should all be in the form "Community_Profile_Report_[YYYYMMDD]_Public.xlsx").

3. Run the R markdown file `COVID19Project3_group4.Rmd` and it will create the figure. 

