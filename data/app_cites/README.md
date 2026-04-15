These data include citations from patent grants to applications. These data come from ‘g_us_application_citation’ (https://data.uspto.gov/bulkdata/datasets -> PatentsView Granted Patent Disambiguated Data). This folder includes 7 different zip files. For ease of download and ease of importing, files are divided by patent number. File “app_cites_non_utility.tsv.zip” includes all non-utility patents. File “app_cites_8m.tsv.zip” includes all citations to applications published beginning November 2003 through patent number 8,000,000. File “app_cites_9m.tsv.zip” includes all patents between patent number 8,000,001 and patent number 9,000,000. Etc, etc. Data are updated through December 2025. These files include the following columns:

| Variable      | Description                                              |
| ------------- | -------------------------------------------------------- |
| patnum        | Patent number                                            |
| appcite_num   | Application number of citation                           |
| appcite_idate | Publication date of citation (mm/yyyy)                   |
| wipo_kind     | Patent kind of citation                                  |
| cited_by      | Person who cited application (examiner, applicant, etc.) |
| sequence      | Patent-level position within citations                   |
