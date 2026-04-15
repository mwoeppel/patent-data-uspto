# patent-data-uspto
Patent data downloaded from the USPTO (and Google) that I have cleaned, organized, and merged. See each folder inside the data folder for the respective README files.




- data/general_info.dta.zip -> includes general info data from the USPTO (https://patentsview.org/download/data-download-tables). These data come from ‘g_patent’, ‘g_application’, and ‘g_figures’. This link includes all general info data for patents granted from January 1976 through December 2024. This file includes the following columns:

| Variable    | Description                               |
| ----------- | ----------------------------------------- |
| patnum      | Patent number                             |
| appnum      | Application number                        |
| fdate       | Filing date of patent (mm/dd/yyyy)        |
| idate       | Issue (grant) date of patent (mm/dd/yyyy) |
| pattype     | Patent type                               |
| apptype     | Application type                          |
| num_claims  | Number of claims                          |
| num_figures | Number of figures                         |
| num_sheets  | Number of drawings                        |
| wipo_kind   | Patent kind                               |
| withdrawn   | 1=withdrawn, 0=not withdrawn              |
| country     | Country of patent (all US)                |

