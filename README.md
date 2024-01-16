# House_Prices_and_Population_Growth

### About the Project:
----------------------

This exploratory data analysis project aims to examine the relationship between population and house prices across decades. The analysis includes a detailed examination of regional and state-level data. The following sub-questions were addressed to facilitate a comprehensive analysis:

1. What are the trends in house prices over time?
2. What are the trends between population density and the proportional change in house prices over time?
3. How have house prices and population changes varied over the following decade ranges:
   - 1990 to 2000
   - 2000 to 2010
   - 2010 to 2019

These questions guided the exploration and provided insights into the dynamics of house prices in relation to population changes across different time periods and geographic regions.

### Data:
---------

We have access to the following data for conducting the analysis:

- State abbreviations and codes.
- Census data providing state-level population values for the years 1975, 2000, 2010, and 2019.
- Census data presenting state-level property values spanning from 1975 to 2019.
- Consumer Price Index data covering the years 1947 to 2019.

### Requirements:
-----------------

This project has been developed using the **R programming language** and the **RStudio IDE**. The implementation of this project requires the following libraries:

- ggplot2
- ggridges
- tidyr
- readxl
- stringr
- ggrepel
- gridExtra
- patchwork
- viridis
- tidyverse
- broom
- gridExtra
- ggpubr

### Analysis:
-------------

The trends across the states over time are not constant. States like West Virginia, Mississippi have shown a drop in house prices from 1975 to 2019, and at the same time, states like California and Washington have shown a significant increase in house prices across the same time period. There is variance across regions too. The South showed slight decrease in prices across years, but all other states showed some increase. In terms of density, the general trend is that price goes up with increase in population density. So, states with higher population density have more expensive housing. Across time periods we see that as population increases, prices generally increase as well. However, between 2000 and 2010 we see that increase in population did not bring about an increase in prices. 
