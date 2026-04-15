These data include inventors of patents (disambiguated) and come from ‘g_inventor_disambiguated’ and 'g_location_disambiguated' (https://data.uspto.gov/bulkdata/datasets -> PatentsView Granted Patent Disambiguated Data). This folder includes 10 different zip files. For ease of downloading and importing, files are divided by patent number. File “inventor_disambig_non_utility.tsv.zip” includes all non-utility patents. File “inventor_disambig_5m.tsv.zip” includes all patents granted beginning January 1976 through patent number 5,000,000. File “inventor_disambig_6m.tsv.zip” includes all patents between patent number 5,000,001 and patent number 6,000,000. Etc, etc. Data are updated through December 2025. These files include the following variables:

| Variable        | Description                         |
|-----------------|-------------------------------------|
| patnum          | Patent number                       |
| inventor_id     | USPTO-generated inventor ID         |
| first_name      | Inventor first name                 |
| last_name       | Inventor last name                  |
| city            | Inventor city                       |
| state           | Inventor state                      |
| country         | Inventor country                    |
| county          | Inventor county                     |
| gender_code     | Inventor gender                     |
| location_id     | USPTO-generated location ID         |
| latitude        | Inventor latitude                   |
| longitude       | Inventor longitude                  |
| state_fips      | State FIPS code                     |
| county_fips     | County FIPS code                    |
