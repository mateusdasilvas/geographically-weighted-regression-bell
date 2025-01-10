# Geographically Weighted Bell Regression

## What is a Geographically Weighted Regression (GWR) Model?

**Geographically Weighted Regression (GWR)** is a spatial modeling technique that allows for examining spatial variation in relationships between variables. Unlike traditional linear regression, which assumes that relationships between variables are constant across space, GWR estimates regression models for each specific location or region, taking into account geographical variations. This makes GWR useful for analyzing geospatial data where spatial structure may influence variable behavior.

## Bell Distribution

The **Bell Distribution** is a new probability distribution for count data, characterized by being **uniparametric** and accommodating the phenomenon of **overdispersion**. Overdispersion occurs when the variability of the data is greater than expected in traditional count models, such as the Poisson distribution. The Bell Distribution is designed to handle this phenomenon, providing more accurate modeling of data exhibiting excessive dispersion.

## Available Files

- **GWR Bell.r**: Contains the R script used to build the **Geographically Weighted Bell Regression** model. This script implements the code necessary to analyze the data and generate the model results.
  
- **Zonas_AC_09_11_Estrat_Tatico2.xls**: Contains the **accident** data for the traffic zones of Fortaleza, Ceará, used for the geographically weighted regression analysis.

- **tabmicro_es_cs.xls**: Contains the **truck fleet** data for the state of Espírito Santo, which is used in conjunction with the accident data to build the regression model.

## How to Use

1. Make sure you have **R** installed on your machine.
2. Open the `GWR Bell.r` file in RStudio or another preferred R editor.
3. Load the data from `Zonas_AC_09_11_Estrat_Tatico2.xls` and `tabmicro_es_cs.xls`.
4. Run the code to build and analyze the geographically weighted Bell regression model.
5. Review the results and adjust the parameters as needed for your analysis.
