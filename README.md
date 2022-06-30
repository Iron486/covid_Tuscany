# Covid-19 Tuscany

The data are related to Tuscany and its provinces. They covered the period from 24/2/2020 to 15/6/2022 and they were updated daily.

Two tables were created: one with data from the entire Tuscany and the other with data from each province within Tuscany (AR, FI, GR, LI, LU, MS, PI, PO, PT, SI) and each medical district of the region (aslCENTRO,aslNO,aslSE).


### **Inspiration**

You can perform an exploratory data analysis of the data, working with `Pandas` or `Numpy`. 

Interesting visualizations can be performed too using, for instance, `Python` libraries to plot the data of the number of deaths, dismissed patients, total and current positives, recoveries etc. 

It might be useful to plot the data in time, working with different date formats too and conducting a time series analysis.

Moreover, this dataset is very good to practice queries using `SQL` or `Pandas`.


### **Collection methodology**

The data were fetched from the following link: https://dati.toscana.it/dataset/open-data-covid19. 

The rows from provinces were separated from the rows related to Tuscany region and some columns were removed from the catalogue since they didn't contain any data.
Furthermore, some columns were transformed from floats to integers, missing values were filled with the integer '0' and the headers were translated to English.

Click the following file [covid_data_Tuscany_cleaning.ipynb](https://github.com/Iron486/covid_Tuscany/blob/main/covid_data_Tuscany_cleaning.ipynb) to take a look at the preprocessing steps.

### **License**

[Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
