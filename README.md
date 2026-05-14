# 🎾 Tennis Surface Specialization Project

## Overview
This project investigates whether tennis players and countries exhibit true surface specialization across clay, grass, and hard courts. The central question is whether performance differences across surfaces reflect genuine specialization or simply variation in exposure and opportunity.

## Data
The dataset includes professional tennis match results aggregated by country, surface, and time period. This data was taken from JeffSackmann's GitHub on ATP matches from 2015 to 2024. It contains information on:
- Match outcomes (wins/losses)
- Surface type (clay, grass, hard)
- Country representation
- Exposure (number of matches played on each surface)
- Win rates and performance metrics over time

## Key Variables
To support the analysis, several derived metrics were created:
- **Win rate by surface** (performance measure)
- **Surface exposure** (share of matches played on each surface)
- **Relative performance** (surface-specific performance vs overall win rate)
- **Specialization score** (difference between best and worst surface performance)

## Visualizations & Methods
This project includes multiple visual approaches:
- **Scatterplots:** Relationship between surface exposure and win rate
- **Heatmap:** Relative performance across surfaces by country
- **Bar Charts:** Surface Exposure and Specialization scores across countries
- **Boxplots (Shiny App):** Direct country-to-country surface comparisons
- **Animated Line Graph:** Changes in surface-specific win rate rankings over time

## Key Findings
- Most countries show relatively small differences in performance across surfaces.
- Surface exposure strongly influences perceived “specialization,” suggesting opportunity may be mistaken for inherent ability.
- Argentina performed significantly worse on grass than on other surfaces, but that can likely be attributed to less experience on grass.
- Overall, the concept of surface specialization appears weaker than commonly assumed.

## Interpretation
The results challenge the traditional narrative of surface specialization in tennis. Instead of fixed surface strengths, performance appears to fluctuate over time and is heavily influenced by exposure and scheduling rather than inherent surface-specific skill.

## Tools Used
- R
- ggplot2
- shiny
- dplyr
- tidyverse

## How to View the Project
- The full write-up is available as a static HTML report.
- Interactive Shiny visualizations are linked within the report.
- Key figures are embedded directly for reproducibility and presentation clarity.

## Author
Annabel Brawn  
University of Virginia  
Sports Analytics & Data Visualization Project
