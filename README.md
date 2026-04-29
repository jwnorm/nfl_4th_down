# The Dan Campbell Effect: Fourth-Down Decision-Making in the National Football League

> **Note:** This repo is related to my final project for *ST 540: Applied Bayesian Analysis* at NC State University.

## Overview

This project concerns analyzing play-by-play data queried from NFL databases using the `nflfastR` package in `R` to determine the impact Detroit Lions head coach Dan Campbell has had on fourth-down decision-making. This includes the number of fourth-down conversion attempts each year as well as assessing the importance of various factors that affect the decision to go for it. This is done by fitting a series of Bayesian **G**eneralized **L**inear **M**ixed **M**odels (GLMMs) with different priors, analogous to frequentist ridge and LASSO regression techniques.

## Data

The data examined is from the last 10 NFL regular seasons, 2016-2017 through 2024-2025. Due to the nature of this analysis, the play-by-play data is limited to fourth-down attempts only.