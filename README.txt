Measuring the Continuing Impact of the COVID-19 Pandemic on Domestic Air Travel
University of Michigan SIADS 593 Winter 2023 Final Project
Adam Packer and Aaron Newman
08-apacker-newmanar

This README file is submitted with our final project package. The contents are as follows:

- README.txt - This file
- 08-apacker-newmanar.pdf - Final project report

- source folder
  - Setup_Notebook.ipynb (Initial processing of COVID-19 and BTS data)
  - Analysis_Notebook.ipynb (Analysis of correlation between COVID-19 cases/deaths and air passenger counts)
  - Predictive_Analysis_Notebook.ipynb (Predictive modeling using Linear Regression and Vector Autoregression)

- data folder
  - BTS Air Travel Data 2020-2022.zip - Contains 3 CSVs files with air travel data for 2020, 2021, and 2022 (Jan-Nov)
  - COVID_Travel_US_Profile.html - Profile (via ydata-profiling) of compiled data at the end of processing the Setup Notebook
  - Compiled_data.pkl - Data compiled in Setup Notebook, used in both the Analysis and Predictive Analysis Notebook
  - code_lookup.csv - Contains mappings of city markets to BTS and Census Bureau five-digit codes
  - df_cbsa_covid_data.pkl.zip - Zipped pickle file of COVID-19 data down to the CBSA level (should be unzipped for use)
  - df_us_covid_data.pkl - Pickle file of COVID-19 data at the US national level
  - full_BTS_data.pkl - Pickle file of processed BTS data produced by the Setup Notebook

Notes for use:

- Please ensure that all data is unzipped and located in the same directory/path as the source notebooks when processing.
- The Setup Notebook is set to read raw data from included CSV files for air travel data and pickle files for COVID-19 data. Cells in the Setup Notebook can be uncommented to read the COVID-19 data directly via API. The user must have an API key in order to do this, and it can be obtained at this web page: https://apidocs.covidactnow.org/#register
- All information for the project has also been posted to Github at https://github.com/newmanar/SIADS593