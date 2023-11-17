world_education_data

# World Educational Data Analysis

## Overview

This project analyzes global educational data, focusing on the Out of School Rate (OOSR) and Completion Rate for primary education, differentiated by gender.

## Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/world-educational-data). Corrections have been made to the latitude and longitude values of some countries.

## Features

-   Calculation of total OOSR and completion rates by summing male and female rates.
-   Data visualization using stacked bar charts to compare male and female rates across countries.
-   Filtering out data with zero values in completion rates for more accurate analysis.

## Visualization

Visualizations include:

-   Stacked bar charts (both vertical and horizontal) for easy comparison of rates.
-   Custom styling for clarity and aesthetic appeal.

## Requirements

-   pandas
-   matplotlib

## Usage

Run the Jupyter Notebook `global_education.ipynb` to generate the analysis and visualizations.

## Contributions

Contributions, suggestions, and improvements are welcome. Please ensure to follow the existing coding style and add relevant tests for any new features.

## License

[MIT License](https://opensource.org/licenses/MIT)
