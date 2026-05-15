# Statistical Computing and Airline Delay Analysis

## Overview

This project was completed for Programming for Data Science module. It uses both Python and R, and the work is divided into two parts.

The first part is a simulation task using the random walk Metropolis algorithm. The second part uses US airline data to analyse flight delays, plane age, and flight diversion.

I am adding this project to my GitHub as part of my portfolio, so I am also using this as a chance to organize the files and document the project more clearly.

## Part 1: Markov Chain Monte Carlo Simulation

The first part focuses on generating samples from this target density:

f(x) = 1/2 exp(-|x|)

The random walk Metropolis algorithm was used to generate simulated values from this distribution. The results were then shown using a histogram and density plot, and compared with the actual density curve.

The sample mean and standard deviation were also calculated. R-hat was used as a convergence check across different proposal standard deviations.

## Part 2: Airline Delay Analysis

The second part uses airline data from the 2009 ASA Statistical Computing and Graphics Data Expo. The analysis used flight data from 1997 to 2006, together with plane and airport information.

The analysis focused on three questions:

1. What days and times are better for minimizing delays?
2. Do older planes tend to have longer delays?
3. What factors are related to flight diversion?

## Tools Used

- Python
- R
- Jupyter Notebook
- R Markdown
- pandas
- NumPy
- matplotlib
- scikit-learn
- dplyr
- ggplot2

## Methods Used

- Random walk Metropolis algorithm
- Markov chain Monte Carlo simulation
- R-hat convergence check
- Data cleaning
- Data merging
- Exploratory data analysis
- Logistic regression
- Coefficient visualization

## Dataset

The airline data comes from the 2009 ASA Statistical Computing and Graphics Data Expo, available through Harvard Dataverse.

Data source: https://doi.org/10.7910/DVN/HG7NV7

The raw airline data files are not included in this repository because the dataset is very large.

## Folder Structure

```text
01-statistical-computing-airline-analysis-project
│
├── data
│   └── README.md
│
├── notebooks_python
│   ├── part1_mcmc_python.ipynb
│   ├── part2a_delay_day_time_python.ipynb
│   ├── part2b_plane_age_delay_python.ipynb
│   └── part2c_diversion_logistic_python.ipynb
│
├── notebooks_r
│   ├── part1_mcmc_r.Rmd
│   ├── part2a_delay_day_time_r.Rmd
│   ├── part2b_plane_age_delay_r.Rmd
│   └── part2c_diversion_logistic_r.Rmd
│
└── reports
    ├── part1_report_mcmc.pdf
    └── part2_report_airline_analysis.pdf