# Project2_NBA
# This is a group project that is part of the Metis Data Science Bootcamp
# The goal of this project is to predict the length of an NBA players career based of their performance teh first two years of their career
## Members:
+ Cianan Murphy

## Methodologies
**1. Obtain data**
- See below for data sources
- Webscrape data from basketball reference from 2000-2019
  - NBA has had many rule changes and advances in sports science, nutrition and training are all factors that can change the longevity of players
- Add coulumns for players Win share in first two years in NBA and the age they entered the league

**2. Clean and prepare data**
- Remove players who are currently in teh league 
- Reomove players who played before the 2000's
  - This isolate players who have played in teh league and retired, that way the data isnt skewed
    
    
**3. Data Analysis**
- Looked at Age entering the league, total career length and Win share over first two years:
  - Heatmap that compares these three values
- Linear Regression of aformentioned variables:
  - With the independent variable being career length
  - Plotted predicted values vs actual values fro career length


## Deliverables
- [Presentation](NBA_per.pdf)
- [Jupyter Notebook for NBA data scraping and cleaninf](Data_scraping.ipynb)
- [Jupyter Notebook Regression Analyis](Regression Analysis.ipynb)
  - [Plosts and data files](data)


## Data Sources

|Description|Source|Link|
|------------|------|-----|
|Plyer stats | Basketball reference | https://www.basketball-reference.com/leagues/NBA_2016_advanced.html |

## Technologies Used
* Jupyter Notebook
* Python
* Libraries
  * Pandas
  * Numpy
  * Matplotlib
  * Seaborn
  * skleran
  * statsmodels
