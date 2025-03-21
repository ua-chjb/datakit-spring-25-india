# datakit-spring-25-india
data sources for financial inclusion, focus India

There are two data sources, from the World Bank Group
1. global view
  - this data is global, aggregated at the country level: with 4 dates per country ranging 2011-2021
  - large number of columns, mostly encoded variables (658, 1232)
  - original data from this link:  https://www.worldbank.org/en/publication/globalfindex/Data
  - 2 csv files have been extracted from this data
    - `global_india.csv` filters based on just India (4, 1232)
    - `global_byregion.csv` filters based on region-level aggregates, ie Southeast Asia, Africa, Latin America, etc (63, 1232)
2. micro data
  - this data zooms in at India-specific data
  - original from this link: https://microdata.worldbank.org/index.php/catalog/4653/get-microdata
  - 1 csv file directly downloaded (after registration wall)
    - **`micro_india` is raw data from the Gallup survey on financial inclusion in india (3000, 119)**
