# Formula1-Project-using-Python-and-SQL
Project is about Formula 1 Racing 
Data i took it from third party developer API -http://ergest/com/mrd/ .It makes the data available for all races.
Eight files we will be taking as part of Project
Circuits CSV
Races CSV
Constructors Single line JSON
Drivers Single line Nested JSON
Results Single line JSON
Pitstops Multi Line JSON
LapTimes Split CSV Files
Qualifying Split MultiLInes JSON
All the files were in CSV Files but converted internally as mentioned format to play with data
We have to ingest all files into the DataLake
Ingested Data must have the right Schema
Ingested Data must be stored in parquet Format
We want to produce Driver Stadings as well as Constructor Stadings for current race year as well as every year from 1950 onwards
We want to find the most dominant drivers and team over the last decade, as well as all time in formula one. And after that we want to rank them in order of their dominance.
And we will create a various visualizations to see the period in which the driver or teams were dominant as well as their level of performance and the dominance. 
We will craete a dashboards from these outcomes.We will craete this dashboard in Azure Databricks 
