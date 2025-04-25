# Remote Work/Telework Dataset Analysis Project
This project is meant to explore how teleworking and working from home can affect workers and their industires. The analysis uses publicically available datasets to help answer the bleow research questions.

`Project.ipynb` is the Jupyter Notebook containing the code, visuals, and analysis.

## Primary Research Questions 
- What percentage of people work from home vs. in person?
- Which industries have the highest telework rates?
- What is the average age and education level of teleworkers?
- How many hours do teleworkers work compared to in-person workers?
- How has COVID-19 impacted telework trends?

## Used DataSets 
- [U.S. Bureau of Labor Statistics](https://www.bls.gov/opub/ted/2023/about-1-in-3-workers-in-management-professional-and-related-occupations-teleworked-november-2023.htm) Special Thanks to U.S. Bureau of Labor Statistics, Office of Publications and Special Studies, Division of Labor Force Statistics, and Office of Publications & Special Studies for the amazing super informative dataset.
- [WFH Research](https://wfhresearch.com/) Special thanks to Barrero, Jose Maria, Nicholas Bloom, and Steven J. Davis, 2021 for the amazing dataset used in their "Why working from home will stick," National Bureau of Economic Research Working Paper 28731.

Both of these datsets are stored on this GitHub in the folder `DataSets/`.
All 4 .csv dataset files are exported from the dataset [telework-tables-2025-03.xlsx](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/telework-tables-2025-03.xlsx) and [WFHtimeseries_monthly.xlsx](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/WFHtimeseries_monthly.xlsx) files.

The [telework-tables-2025-03.xlsx](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/telework-tables-2025-03.xlsx) dataset holds:
- [telework-tables(Average_hours)-2025-March-(T4).csv](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/telework-tables(Average_hours)-2025-March-(T4).csv)
- [telework-tables(Telework_Status)-2025-March-(T1).csv](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/telework-tables(Telework_Status)-2025-March-(T1).csv)

The [WFHtimeseries_monthly.xlsx](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/WFHtimeseries_monthly.xlsx) dataset holds:
- [WFHtimeseries_monthly_(Before-During_COVID).csv](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/WFHtimeseries_monthly_(Before-During_COVID).csv)
- [WFHtimeseries_monthly_(Indrustry).csv](https://github.com/Joba19/DSCI-235-Project/tree/main/DataSets/WFHtimeseries_monthly_(Indrustry).csv)

## How to Run
1. Open the Juptyter File `Project.ipynb`.
2. All data and datasets used in the Juptyter file is from this GitHub making no other downloading necessary.
3. Run all cells from top to bottom to see the analysis.

## TroubleShoot:
If you run into an errors its likely due to `pandas` or `matplotlib.pyplot` not being installed, to fix this follow the below directions:
1. Open a new python Terminal and run the line `pip install pandas`
2. In the same Terminal run the line `pip install matplotlib`
3. Run the cells in the `Project.ipynb` Juptyter file from top to bottom.

This Project is purley for educational purposes only and shouldn't be used otherwise.