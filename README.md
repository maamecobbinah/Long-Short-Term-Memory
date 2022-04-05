# Forecasting Unemployment Rate Canada
### Objective:
The objective is to use various data visualization technique to draw insights from Labour Statistics Data priovided by Statistics Canada from 1997 to 2021.
The projects looks at Unemployment Rate in particular to see trends overtime. Once EDA is done the dataset is cleaned (total are aggregated and oonly needed features are selected) and a simple LSTM  model is created to understand and predict unemployment trends overtime

### DataSet:
Two datasets are used in this project. The orginal for EDA and cleaned version for LSTM modeling. See detail description of fields below.
1. Province: This shows the Canadian Province or Territory where the particular statistics was associated to 
2.	Year: Year Reference period
3.	Month: Month reference period
4.	Year ID:  A numeric number associated to a particular year
5.	Month ID: A numeric number associated with the particular year
6.	Date:  A date stamp associated with the metric
7.	Age Group; Population Age group (here only 15years and over is considered)
8.	Sex: Either Male or Female
9.	UOM: Unit of Measurement in Persons
10.	Coordinates: A metric used by Survey Canada is structure specific geographical locations
11.	Latitude: Latitude
12.	Longitude: Longitude
13.	Employed: Number of Employed People
14.	Labour Force: Total number of people within the labour force
15.	Unemployed: Number of unemployed individuals
16.	EI Benefiaries: Number  of People receiving EI regular Benefits 
