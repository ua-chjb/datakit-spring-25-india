# datakit-spring-25-india
data sources for financial inclusion, focus India

Data sources original links
1. World Bank Group
 - a). global view
    - this data is global, aggregated at the country level, with a large number of columns, mostly encoded variables (658, 1232). original data from this link:  https://www.worldbank.org/en/publication/globalfindex/Data
      - 3 csv files have been extracted from this data
      - `global_all.csv` whole dataset (mostly not India) (658, 1232)
      - `global_india.csv` filters based on just India (4, 1232)
      - `global_byregion.csv` filters based on region-level aggregates, ie Southeast Asia, Africa, Latin America, etc (63, 1232); for comparisons
 - b). country-specific view
    - this data zooms in at India-specific data, original from this link: https://microdata.worldbank.org/index.php/catalog/4653/get-microdata
      - 1 csv file directly downloaded (after registration wall)
      - **`micro_india` is raw data from the world bank group survey on financial inclusion in india (3000, 119)**
3. data.gov.in
  - a). by state
    - internet presence by state, original data from: https://www.data.gov.in/resource/stateut-wise-details-internet-penetration-internet-subscribers-100-population-urbanrural
      - 1 csv file downloaded, *plenty more data available at data.gov.in*
      - `internet_by_state_2024.csv` small dataset organized by state (37, 8)
