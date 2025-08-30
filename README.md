# 1C_web_scraping_and_data_management_in_R

This repository contains two assignment submissions for my 1C course in R:
1. Scrapes and stores the course titles, urls and descriptions from the Essex Summer School website.
2. Scrapes the relevant data from fixed Wikipedia tables for GDP per capita and democracy indices, stores them in an SQLite DB, and plots the data to visually examine whether a higher GDP per capita is indicative of a better quality democracy. The Wikipedia sites are fixed by revision IDs to avoid changes over time.

The html files were rendered from the Quarto (.qmd) files, and contain the full report output per assignment.


## Getting started

- Clone/pull this repository.
- Restore the exact package versions I used in these assignments (for reproducibility purposes) by typing `renv::restore()` in R / RStudio from the project root folder. This loads the renv.lock json file (if not done automatically). You may have to `install.packages("renv")` first. 
- The renv.lock file applies to both assignments.
- You can find the R version used (4.5.1) inside the renv.lock file too.
