# Access CDC WONDER for SCD Trends in Young and Middle-Aged Persons (15-54 yo)

- Mortality data was obtained by accessing the [CDC WONDER database](https://wonder.cdc.gov/ucd-icd10.html). Upon agreement of the terms of use we selected the following non-default options:
  - Section 1: 'Organize table layout'
    - Overall trend: Group results by 'Year'
    - Race: Group results by 'Year' _and 'Race'_
    - Sex: Group results by 'Year' _and 'Gender'_
  - Section 3: 'Select demographics'
    - Select ages 15-54 years old (Hint: use the Shift key to select multiple age ranges)
  - Section 6: 'Select cause of death'
    - Specify the following ICD-10 Code: `I46.1 (Sudden cardiac death, so described)`

# Data Files

- Data are available as processed CSV files in the [data](./data) directory
- Screenshots of results for each query of the CDC WONDER database are in the [screenshots](./screenshots) directory:
  - [Overall trends](./screenshots/scd-overall-webpage.pdf)
  - [Trends by White vs Black race](./screenshots/scd-race-webpage.pdf)
  - [Trends by Male vs Female sex](./screenshots/scd-sex-webpage.pdf)