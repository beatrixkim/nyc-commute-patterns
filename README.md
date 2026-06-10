# nyc-commute-patterns
Statistical analysis of COVID19-driven shifts in Manhattan commute patterns. Scrollytelling format built using R and Quarto with data from the American Community Survey (2019 and 2023).

## Project Site
See the scrollytelling page [here](https://beatrixkim.github.io/nyc-commute-patterns/)

## Built With
R (ggplot2, tidyverse) and Quarto

## Research Question
Among employed Manhattan residents, is there a relationship between 2019 versus 2023 workplace changes and commute times, and do these changes vary between white-collar and blue-collar workers?

## Methods
- Two-sample proportion z-test for remote work adoption
- Wilcoxon rank-sum test for median commute time differences
- OLS regression with interaction term (year × occupation type) on log-transformed commute times

## Structure
- `index.qmd` — main file with R code
- `_extensions/` — closeread extension for scrollytelling
- `_quarto.yml` — project configuration
- `_publish.yml` — page publishing configuration

## Notes
Built as a collaborative course project (STAT260, Fall 2025) with Sabrina Wang.
