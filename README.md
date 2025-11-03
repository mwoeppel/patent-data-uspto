# patent-data-uspto
Patent data downloaded from the USPTO (and Google) that I have cleaned, organized, and merged.

- data/us_cites -> includes US citations data from Google Patents (1926-1975) and the USPTO (1976-2024). The citations from Google Patents were scraped by Elif Guler. Note that citations were not officially included on patent documents until February 1947 (Nicholas, 2010). The USPTO data come from ‘g_us_patent_citation’ (https://patentsview.org/download/data-download-tables). This folder includes 11 different zip files. For ease of download and ease of importing, files are divided by patent number. File "us_citations_1926_1975.csv.zip" includes all patents issued beginning 1926 through December 1975. File “us_cites_non_utility.tsv.zip” includes all non-utility patents. File “us_cites_5m.tsv.zip” includes all patents issued beginning January 1976 through patent number 5,000,000. File “us_cites_6m.tsv.zip” includes all patents between patent number 5,000,001 and patent number 6,000,000. Etc, etc. These files includes the following columns:

| Variable      | Description                                         |
| ------------- | --------------------------------------------------- |
| patnum        | Patent number                                       |
| patcite_num   | Patent number of US citation                        |
| patcite_idate | Issue (grant) date of US citation (mm/yyyy)         |
| wipo_kind     | Patent kind of US citation                          |
| cited_by      | Person who cited patent (examiner, applicant, etc.) |
| sequence      | Patent-level position within US citations           |



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


- 
