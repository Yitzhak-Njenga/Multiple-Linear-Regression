# Project Overview: Home Renovation Impact Analysis

## Introduction
This GitHub repository contains our comprehensive analysis project exploring how various home renovations impact property values in a northwestern county. The goal is to provide homeowners and real estate agencies with data-driven insights to make informed renovation decisions.

## Objective
The primary aim of this study is to understand the correlation between home renovations and the resulting change in property values. This analysis will assist real estate agencies in offering evidence-based renovation advice to homeowners, thereby enhancing client satisfaction and improving the market value of properties.

## Methodology
The project employs linear regression modeling to analyze the effects of different renovation projects on home prices. Linear regression, a statistical method, helps us predict the impact of various factors like square footage, year built, number of bathrooms, etc., on the house's sale price. The methodology section in this repository delves deeper into the specifics of our linear regression approach, detailing how we used this model to draw actionable insights from our data.

## Regression Results
- For a house with `sqft_living`, `yr_built`, and `floors` of 0 (nonsensical), as well as `month` and `grade` of January and Poor respectively, we would expect a price of about `$6,908,865`

- This is not a valid price, since a house with `sqft_living` 0 is not valid either.

- For each increase of 1 in `sqft_living`, we see an associated increase in `price` of about `$156`

- For each increase of 1 in `yr_built`, we see an associated decrease in `price` of about `$-3,530`

- For each increase of 1 in `floors`, we see an associated increase in `price` of about `$41,108`

- For each increase of 1 in `sqft_above`, we see an associated decrease in `price` of about `$-53`

- For each increase of 1 in `bathrooms`, we see an associated increase in the `price` of about `$54,226`

- For each increase of 1 in `bedrooms`, we see an associated decrease in `price` of about `$-31,711`

- Breaking down the `month`:

- For a house sold in `May` compared to a house sold in `January`, we see an associated increase in `price` of about `$17,399`

- For a house sold in `March` compared to a house sold in `January`, we see an associated increase in `price` of about `$36,944`

- For a house sold in `April` compared to a house sold in `January`, we see an associated increase in `price` of about `$43,353`

- Breaking down the `grade`:

- For a house of `grade_10VeryGood` compared to a house of `grade_3Poo`r, we see an associated increase in `price` of about `$546,142`

- For a house of `grade_11Excellent` compared to a house of `grade_3Poor`, we see an associated increase in `price` of about `$841,035`

- For a house of `grade_12Luxury` compared to a house of `grade_3Poor`, we see an associated increase in `price` of about `$1,381,427`

- For a house of `grade_13Mansion` compared to a house of `grade_3Poor`, we see an associated increase in `price` of about `$2,521,888`

## Key Findings
We discovered several trends, such as the positive impact of adding living space or bathrooms on a home's value and the surprising decrease in value with newer construction years. These findings are presented in a manner accessible to non-technical stakeholders, focusing on the practical implications of our statistical analysis.

## Repository Structure
`Data/`: Contains the datasets used in our analysis.

`.pdf/`: Includes the non-technical presentation slides. (`Maximizing Property Value`)

`Student.ipynb/`: Jupyter Notebooks with detailed code and comments explaining the analysis process.

## Usage
The repository is structured to provide a comprehensive understanding of our analysis. The Jupyter Notebooks in the Notebooks/ directory offer an in-depth look at the data processing and analysis steps. While these notebooks contain technical content, they are annotated to ensure readability even for those with minimal coding background.

## Conclusion
Our analysis bridges the gap between speculative renovation decisions and data-driven strategies. By leveraging the insights from our study, homeowners and real estate agencies can make more informed decisions, potentially leading to increased property values and client satisfaction.

## The Team
- Yitzhak Njenga

- David Mwangi

- Valerie Vinya

- Earl Chirchir

- Ann Karuga

- Alice Nyamongo
