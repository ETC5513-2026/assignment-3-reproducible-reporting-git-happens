# ETC5513 Assignment 3

Group Members:

* Alex Delamer
* Duc Hoang
* Aatish Prasad
* Kishori Akola

## Topic: Online Retail Sales Performance Analysis (2018–2019)

- ETC5513 - Collaborative and Reproducible Practices - Assignment 3

- Authors: Alex Delamer, Duc Hoang, Aatish Prasad, Kishori Akola

## Overview

This project analyses one year of transactional sales data from a UK-based online retailer (December 2018 – December 2019). The analysis examines revenue trends, market performance, customer basket behaviour, and cancellation patterns across UK and international markets.

## Repository Structure

| File / Folder | Description |
|---|---|
| `data/` | Raw dataset |
| `media/` | Images  |
| `renv/` | R package environment (managed by renv) |
| `report_files/` | Auto-generated report output files |
| `presentation_files/` | Auto-generated presentation output files |
| `report.qmd` | Main analysis report (Quarto source) |
| `report.html` | Rendered report |
| `report.pdf` | Rendered report |
| `presentation.qmd` | Presentation slides (Quarto source) |
| `presentation.html` | Rendered presentation |
| `references.bib` | Bibliography (APA 7) |
| `apa.csl` | APA 7 citation style file |
| `style.css` | Custom styling |
| `renv.lock` | Package version lockfile |
| `.Rprofile` | renv autoloader |
| `.gitignore` | Custom .gitignore files/folders |


## How to Run

1. Clone the repository
2. Open the project in RStudio
3. Restore the package environment:


> r   renv::restore()

4. Render the report or presentation:

> r   quarto::quarto_render("report.qmd")
   quarto::quarto_render("presentation.qmd")

## Data Source

Kaggle - [E-commerce Business Transaction by Gabriel Ramos](https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business).