# bootcamp-group_project-1

Business Questions:

By city size in the West Coast, which cities had the highest and lowest rates per capita of covid19
Do rates of covid19 differ based on local policies implemented (where do we get data of locked down period)

Steps for Project Completion:

Datasources:

1- Citipy: pull cities on the West Coast, (CA, WA, OR) (you can choose by coordinates)
2- https://covidtracking.com/data/api (or other libraries) to access the number of covid cases on a specific timeframe 
3- CensusData: pull population size by cities on the West Coast (data can be choosen by zipcode)
4- Locked down duration data cdc

Data Analysis:

- cities will be binned by population size
- we wil compare the city bins and covid19 cases per capita (3 bins: small, medium, large cities)
- we will include a heat map of cities by cases
- timeframe: January - October
- average number of covid19 cases per bin size
- average number of covid19 cases per State


List of Visualizations:

- 1 heat map covid19 by city
- 1 line graph of all daily cases per state overtime
- 3 bar charts (CA, OR, WA) grouped (bins) bar chart of average monthly cases per state
- 1 boxplots per bin (small, medium, large cities), average or median covid19 cases per capita between Jan-Oct

Tools:

- jupyter notebook
- api calls or csv
- libraries