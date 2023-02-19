# SIADS593 (08-apacker-newmanar)

### Measuring the Continuing Impact of the COVID-19 Pandemic on Domestic Air Travel
### University of Michigan SIADS 593 Winter 2023 Final Project
### Adam Packer and Aaron Newman

Contents:
- README.md - This file
- 08-apacker-newmanar.pdf - Final project report
- data/ (Note: All data should be placed in the same directory/path as the source notebooks in order to function correctly)
  - BTS Air Travel Data 2020-2022.zip - Contains 3 CSVs files with air travel data for 2020, 2021, and 2022 (Jan-Nov)
  - COVID_Travel_US_Profile.html - Profile of compiled data at the end of processing the Setup Notebook
  - Compiled_data.pkl - Data compiled in Setup Notebook, used in both the Analysis and Predictive Analysis Notebook
  - code_lookup.csv - Contains mappings of city markets to BTS and Census Bureau five-digit codes
  - df_cbsa_covid_data.pkl.zip - Zipped pickle file of COVID-19 data down to the CBSA level (should be unzipped for use)
  - df_us_covid_data.pkl - Pickle file of COVID-19 data at the US national level
  - full_BTS_data.pkl - Pickle file of processed BTS data produced by the Setup Notebook 
- source/
  -  Setup_Notebook.ipynb - Initial processing of COVID-19 and BTS data
  -  Analysis_Notebook.ipynb - Analysis of correlation between COVID-19 cases/deaths and air passenger counts
  -  Predictive_Analysis_Notebook.ipynb - Predictive modeling using Linear Regression and Vector Autoregression

Notes for use:
- COVID-19 raw data can be obtained through the COVID Act Now [website](https://covidactnow.org). Instructions for obtaining an API key are provided [here](https://apidocs.covidactnow.org/#register).
- The notebooks in the source directory assume that all referenced data are in the same path/directory.
- Any file in the data directory that is zipped must be unzipped for use.
