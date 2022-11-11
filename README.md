# Group Project Repository for the UCLA Extension EDA Course

## Structure

Raw data is stored in the 'data' directory. Each variable had its own csv file containing the data, and two csv's containing the metadata for the variables and country codes. The data was downloaded from the [World Bank](http://data.worldbank.org/indicator) and the [World Development Indicators](http://databank.worldbank.org/data/reports.aspx?source=world-development-indicators).

The 'code' directory contains the Python/R scripts used to clean the data, create the final data set, and create the graphs for the presentation. Descriptions of the scripts are below:

1. ***join_data.ipynb*** : This script joins the data from the different csv's into one data frame. It also cleans the data by removing rows with missing values and only keeping data from the year 2019. The final data set is saved as a csv in the 'output' directory as 'joined_data.csv'.

The 'output' directory contains the final data set, as well as the plots used in the final presentation. A description of the files/plots is below:

1. ***joined_data.csv***: The final data set used for the presentation. It contains the data from the different csv's joined together, as well as the cleaned data. The data is from the year 2019. The columns are as follows:

    - **Country Name**: The name of the country
    - **Country Code**: The country code
    - **EG.CFT.ACCS.ZS**: Access to clean fuels and technologies for cooking (% of population)
    - **EG.ELC.ACCS.ZS**: Access to electricity (% of population)
    - **EG.FEC.RNEW.ZS**: Renewable energy consumption (% of total final energy consumption)
    - **EN.ATM.CO2E.PC**: CO2 emissions (metric tons per capita)
    - **SP.DYN.LE00.IN**: Life expectancy at birth, total (years)
    - **SP.POP.TOTL**: Population, total