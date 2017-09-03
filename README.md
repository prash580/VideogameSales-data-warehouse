# VideogameSales-data-warehouse
Creating a data warehouse to store video game rating and sales and visualizing the data

Data Sources
- Data was scraped from the official IGN website for the ratings of video games : http://ie.ign.com/reviews/games
- Sales data was scraped from Vgchartz website : http://www.vgchartz.com/gamedb/
- The ratings of Video game platforms was acquired by R Sentiment analysis(code attached).

Staging and Data Cleaning
- The data was stored in the form of SQL Tables in SQL Server Management Studio.
- Data cleaning and ETL was done using SQL Server Integration Services(SSIS) in Microsoft Visual Studio.
- Cleaned data was stored in the form of normalized SQL Tables.

Cube creation and Visualization
- The tables were divided into dimension tables and fact tables with fact tables storing the numberical values.
- SQL Server Analysis Services (SSAS) was used to build a cube from Dimensions and Fact tables.

Visualization
- The cube was next imported to Tableau directly from SSAS and visualization was performed.

