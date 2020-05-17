# Google Play Store Apps

**About**     
The key question focuses on predicting app installs using essential predictors. Various Supervised techniques can be utilized in this problem. Additionally, data has enormous potential to derive various other insights as well.

**Data**       
Web Scrapper API is created in Python using Beautiful Soup library which scraps the data from Google Play Store. Webscraper API can be found at https://github.com/saxenasomil/data_science_projects/tree/master/2.%20Web_Scrapped_Apps_ML/webScraper

This API stores data in a CSV file (named apps_additional_info.csv which will be used as the source dataset.

This project will utilize three data sources:

1.  **apps_additional_info.csv** - This data file contains the additional information needed about 10000 apps present on Google Play Store.It has columns such as App, Interactive Elements, Permissions, Report, Offered By, Developer, In-app Products. The data was last scraped on 04/09/20.

Above data source is scraped using WebScrapper API.
Below source file is from Kaggle:

2.  **googleplaystore.csv** - This dataset file is contains info about 10000 apps. It has columns such as App, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Current Ver, Android Version.

**Assumptions**        
None 

**References**     
https://www.kaggle.com/lava18/google-play-store-apps