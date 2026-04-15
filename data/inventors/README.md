These data include inventors of patents and come from ‘g_inventor_not_disambiguated’ and 'g_location_not_disambiguated' (https://data.uspto.gov/bulkdata/datasets -> PatentsView Granted Patent Disambiguated Data). This folder includes 10 different zip files. For ease of downloading and importing, files are divided by patent number. File “inventor_non_utility.tsv.zip” includes all non-utility patents. File “inventor_5m.tsv.zip” includes all patents granted beginning January 1976 through patent number 5,000,000. File “inventor_6m.tsv.zip” includes all patents between patent number 5,000,001 and patent number 6,000,000. Etc, etc. Data are updated through December 2025. These files include the following variables:

| Variable        | Description                         |
|-----------------|-------------------------------------|
| patnum          | Patent number                       |
| inventor_id     | USPTO-generated inventor ID         |
| first_name      | Inventor first name                 |
| last_name       | Inventor last name                  |
| rawlocation_id  | USPTO-generated raw location ID     |
| location_id     | USPTO-generated location ID         |
| city            | Inventor city                       |
| state           | Inventor state                      |
| country         | Inventor country                    |
