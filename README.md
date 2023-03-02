# F1FastestLap2020-2022Seasons
Includes dataset of 'DHL Fastest Lap' in Formula One for the 2020, 2021, and 2022 seasons scraped from Formula One website. Data is characterized by Year,  Grand Prix, Driver, Car, and Lap Time. Repository includes processed cvs dataset, Jupyter notebook including visualizations and analysis, and README + LICENSE information.

The goal of this project was to identify trends over the last three Formula One seasons by utilizing webscraping, data cleaning, data curation, and data anlysis methods learned in i310D. In order to do so, I used Python to scrape the DHL Fastest Lap data from the Formula One website over the last three years. I employed the ETL pipeline to clean, normalize, and proof the data, ensuring its quality and then proceeded to obtain descriptive statistics, develop informative analyses and visualizations, and make interesting observations over the nature of Formula One competition. 

Data was scraped from the following links: 
  https://www.formula1.com/en/results.html/2022/fastest-laps.html
  https://www.formula1.com/en/results.html/2021/fastest-laps.html
  https://www.formula1.com/en/results.html/2020/fastest-laps.html

LICENSE: This project is licensed under the terms of the MIT license. 

F1 DHL Fastest Lap Dataset: Data Types & Descriptions
  
Column: Dtype

Year: int64
    - Year (2020-2022) in which the recorded lap time occured. 

Grand Prix: object
    - Grand Prix location recorded lap time occured at. 

Driver: object
    - Driver of whom is responsible and achieved the recorded lap time. 

Car: object
    - Formula One Car Racing Team that the driver obtained the recorded lap time on behalf of. 

Lap Time: float64
    - Recorded lap time in 'MM.SS' (minutes.seconds) form. 
      Ex: 1.24 --> 1 minute and 24 seconds
  
CONCLUSION: 

dtypes: float64(1), int64(1), object(3) 

There are 60 counts of all data types above. 
 
 


  
