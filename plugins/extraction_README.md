EXTRACTION 

1.  get request data from Open Database of Philly (Apache Airflow) 

    a. house public properties (main datasets to focus (more than 500k row, and 70 columns))
        - house related location data, such as Philly public school, Philly healthcare service, crime rate, police stations, etc)(total 9 datasets, preliminary clean some unknown data via airflow)
    b.  API yahoo finance data from housing index stock (real estate companies ETF) (airflow)
        - This data will be use to compare the housing price trend data from part house public properties
    c. Housing market data from Melissa.com real estate website.(download and use airflow DAGs to combine)


### HOUSING PREDICTION 
Jupyter notebook will be used to load the data with applying SQL query for data analysis and pridction model building. The data visualization will be also performed with matplotlib and other data visulization tools. 

 Also, we will update some daily housing information in the Philly area, to allow us to have a parallel view of the price prediction study. A streaming API data will be added.