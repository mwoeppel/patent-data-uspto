These data include assignees to patent grants and come from ‘g_assignee_not_disambiguated’, 'g_location_not_disambiguated', and 'g_location_disambiguated' (https://data.uspto.gov/bulkdata/datasets -> PatentsView Granted Patent Disambiguated Data). This folder includes 10 different zip files. For ease of downloading and importing, files are divided by patent number. File “assignee_non_utility.tsv.zip” includes all non-utility patents. File “assignee_5m.tsv.zip” includes all patents granted beginning January 1976 through patent number 5,000,000. File “assignee_6m.tsv.zip” includes all patents between patent number 5,000,001 and patent number 6,000,000. Etc, etc. Data are updated through December 2025. These files include the following variables:

| Variable          | Description                              |
|-------------------|------------------------------------------|
| patnum            | Patent number                            |
| assignee_id       | USPTO-generated assignee ID              |
| organization      | Assignee name                            |
| city              | Assignee city                            |
| state             | Assignee state                           |
| country           | Assignee country                         |
| disambig_city     | Disambiguated assignee city              |
| disambig_state    | Disambiguated assignee state             |
| disambig_country  | Disambiguated assignee country           |
| latitude          | Assignee latitude                        |
| longitude         | Assignee longitude                       |
| county            | Assignee county                          |
| state_fips        | State FIPS code                          |
| county_fips       | County FIPS code                         |
| type              | Assignee type                            |
| location_id       | USPTO-generated location ID              |
