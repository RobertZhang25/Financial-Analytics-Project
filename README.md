## Financial-Analytics-Project
> **Analysis of the characteristics in explaining stock returns over the 5 financial market crisis from 1987 - 2022.**

### ***Research Objective:*** Analyzing relationship between stock returns $(R_i)$ and fundamental ratios around 5 market crashes
> **Overview:** Steps are presented below for analyzing monthly average returns during **market crashes in 1987, 2000, 2008, 2020, and 2022.** We first filter the `CRSP` dataframe (obtained from Wharton) for specific stock return data (`crash_return`) during the distinct market crash periods, and then merge the resulting df with the corresponding `Compustat` data (also from Wharton) to calculate regression coefficients based on various fundamental ratios. Interpretations of regression coefficients and results are discussed for each market period. 
