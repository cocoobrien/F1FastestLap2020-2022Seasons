# F1FastestLap2020-2022Seasons

This project encompasses a comprehensive dataset featuring the 'DHL Fastest Lap' records from the Formula One seasons of 2020, 2021, and 2022. The dataset, meticulously extracted from the official Formula One website, is organized by key parameters such as Year, Grand Prix, Driver, Car, and Lap Time.

The repository is equipped with a refined CSV dataset, a Jupyter notebook containing insightful visualizations and in-depth analysis, along with essential README and LICENSE information.

The primary objective of this endeavor was to discern overarching trends across the last three Formula One seasons, employing advanced techniques in web scraping, data cleaning, curation, and analysis acquired through the i310D curriculum. The methodology involved Python scripting to scrape the DHL Fastest Lap data, followed by the implementation of an ETL (Extract, Transform, Load) pipeline to ensure data quality through cleaning, normalization, and validation processes. Subsequently, the dataset underwent a thorough examination, leading to the extraction of descriptive statistics, the formulation of informative analyses and visualizations, and the generation of compelling insights into the dynamics of Formula One competition.

The data extraction process focused on the following Formula One season links:

- [2022 Fastest Laps](https://www.formula1.com/en/results.html/2022/fastest-laps.html)
- [2021 Fastest Laps](https://www.formula1.com/en/results.html/2021/fastest-laps.html)
- [2020 Fastest Laps](https://www.formula1.com/en/results.html/2020/fastest-laps.html)

The project is released under the MIT license, emphasizing the commitment to openness and collaboration.

F1 DHL Fastest Lap Dataset: Data Types & Descriptions

| Column     | Dtype   |
|------------|---------|
| Year       | int64   | Year (2020-2022) of the recorded lap time. |
| Grand Prix | object  | Location of the Grand Prix where the lap time occurred. |
| Driver     | object  | Driver responsible for and achieving the recorded lap time. |
| Car        | object  | Formula One Car Racing Team associated with the recorded lap time. |
| Lap Time   | float64 | Recorded lap time in 'MM.SS' (minutes.seconds) format. (e.g., 1.24 represents 1 minute and 24 seconds) |

CONCLUSION:

dtypes: float64(1), int64(1), object(3)

The dataset consists of 60 entries across all the aforementioned data types.
 
 


  
