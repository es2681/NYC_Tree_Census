# NYC Tree Census

## Overview
Between 2015 and 2016, the New York City Department of Parks & Recreation (DPR) conducted their third street tree census under the TreesCount! program, the largest municipal urban forestry project in US history. Over 2,200 volunteers as well as professional surveyors mapped 666,134 street trees on 131,488 blocks, walking a total of 11,093 miles. Previous surveys were conducted in 1995 and 2005. For further information, see the [TreesCount!](https://www.nycgovparks.org/trees/treescount) website.

The purpose of this evaluation was to identify the total number of live trees in each borough, as well as the prevalence of tree species, and to determine the number of trees per 1,000 people in each zip code. The data was analyzed using Python and a Jupyter Notebook. 

## Resources
- NYC Parks & Recreation: [2015 Street Tree Census - Tree Data](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/uvpi-gqnh)
- World Population Review: [2022 Population in New York State by Zip Code](https://worldpopulationreview.com/zips/new-york)

## Results
### Number of Trees per Borough
As indicated below, there are 652,168 documented live trees in NYC. Queens is the borough with the largest number of live trees, totaling 237,970 trees, while Manhattan has the fewest number of trees with 62,427 trees. 

| Borough     | Number of Trees |
| ---      | ---       |
| Manhattan | 62,427        |
| Brooklyn     | 169,744      |
| Queens | 237,970         |
| Bronx | 80,584        |
| Staten Island | 101,443         |
| **Total** | **652,168**        |


### Top Tree Species per Borough
The TreesCount! survey identified 132 individual species of trees in NYC. See the [NYC_Trees_Count.csv](https://github.com/es2681/NYC_Tree_Census/blob/main/NYC_Trees_Count.csv) file for a count of all tree species. Listed below are the top ten tree species found in each borough. Four species (Honeylocust, London Planetree, Callery Pear, and Pin Oak) were in the top ten for all boroughs. American Elm and American Linden made the top ten only in Manhattan, while Green Ash was only in the top ten for Queens. Both Sweetgum and Maple were of the ten most common species for only Staten Island. 
| Rank | Manhattan | Brooklyn | Queens | Bronx | Staten Island |
| --- | --- | --- | --- | --- | --- | 
| 1 | Honeylocust | London Planetree | London Planetree | Honeylocust | Callery Pear |
| 2 | Callery Pear | Honeylocust | Pin Oak | London Planetree | London Planetree |
| 3 | Ginkgo | Pin Oak | Honeylocust | Pin Oak | Red Maple |
| 4 | Pin Oak  | Japanese Zelkova | Norway Maple | Callery Pear | Pin Oak | 
| 5 | Sophora | Callery Pear | Callery Pear | Japanese Zelkova | Cherry |
| 6 | London Planetree | Littleleaf Linden | Cherry | Cherry | Sweetgum |
| 7 | Japanese Zelkova | Norway Maple | Littleleaf Linden | Littleleaf Linden | Honeylocust |
| 8 | Littleleaf Linden | Sophora | Japanese Zelkova | Norway Maple | Norway Maple |
| 9 | American Elm | Cherry | Green Ash | Ginkgo | Silver Maple |
| 10 | American Linden | Ginkgo | Silver Maple | Sophora | Maple |


### Top Zipcodes for Higest Number of Trees per 1,000 People
Queens and Staten Island had the greatest number zipcodes with high tree/person densities, with 7 and 5 zipcodes in the top 15 zipcodes respectively. The Bronx had 2 zipcodes with the densest tree/person populations. No zipcodes ranked in the top 15 for Brooklyn or Manhattan.
| Rank  | Neigbhorhood | Borough | Zipcode | # of Trees/<br>1,000 People | 
| --- | --- | --- | --- | --- | 
| 1 | Little Neck | Queens  | 11363 | 385.01 |
| 2 | Tottenville | Staten Island | 10307 | 355.70 |
| 3 | Rossville /<br>Pleasant Plains | Staten Island | 10309 | 355.45 |
| 4 | Arden Heights /<br>Eltingville | Staten Island | 10312 | 347.86 |
| 5 | Glen Oaks | Queens | 11004 | 265.27 | 
| 6 | Bellerose | Queens | 11426 | 236.11 | 
| 7 | New Dorp | Staten Island | 10306 | 234.16 |
| 8 | Douglaston | Queens | 11362 | 232.40 |
| 9 | Great Kills | Staten Island | 10308	| 230.62 |
| 10 | Pelham Bay | Bronx | 10464 | 229.09 |
| 11 | Whitestone | Queens | 11357 | 228.82|
| 12 | Bayside | Queens | 11361 | 218.30|
| 13 | Fresh Meadows | Queens | 11366 | 203.48 |
| 14 | Hunts Point | Bronx | 10474 | 202.15 |
| 15 | Oakland Gardens | Queens | 11364 | 185.86|
