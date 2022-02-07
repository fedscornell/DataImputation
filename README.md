# Completing Under-Determined Spatial Agri-Food Data Systems: A Flexible  Bayesian Framework

This repository is created to share data and code of the vegetable and livestock data imputation program. 

## Data source

| Data   Characteristic         | Vegetable                                                                                                                                                                                                                                                                    | Cattle                                                                                                                                                                                                                 |
|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Source   table: COA Chapter 1 | [Table 36. Vegetables,   Potatoes, and Melons Harvested for Sale: 2017 and 2012](https://www.nass.usda.gov/Publications/AgCensus/2017/Full_Report/Volume_1,_Chapter_1_US/st99_1_0036_0036.pdf)                                                                                                                                                                                            | [Table 12. Cattle and Calves –   Inventory: 2017 and 2012](https://www.nass.usda.gov/Publications/AgCensus/2017/Full_Report/Volume_1,_Chapter_1_US/st99_1_0011_0012.pdf)                                                                                                                                                            |
| Source   table: COA Chapter 2 | [Table 29. Vegetables,   Potatoes, and Melons Harvested for Sale: 2017 and 2012](https://www.nass.usda.gov/Publications/AgCensus/2017/Full_Report/Volume_1,_Chapter_2_US_State_Level/st99_2_0029_0029.pdf)                                                                                                                                                                                            | [Table 11. Cattle and Calves –   Inventory and Sales: 2017 and 2012](https://www.nass.usda.gov/Publications/AgCensus/2017/Full_Report/Volume_1,_Chapter_1_US/st99_1_0011_0012.pdf)                                                                                                                                                  |
| Unit of   observation         | Total harvested acreage by   vegetable category                                                                                                                                                                                                                              | Inventory of head of cattle by   cattle category                                                                                                                                                                       |
| Geographic levels             | National, State, County                                                                                                                                                                                                                                                      | National, State, County                                                                                                                                                                                                |
| Size categories               |  0.1 to 0.9 acres, 1.0 to 4.9 acres, 5.0 to   99.9 acres, 100.00 to 249.9 acres, 250.0 to 499.9 acres, 500.0 to 749.9   acres, 750.0 to 999.9 acres, 1000.0 acres or more, 1000.0 to 999.9 acres,   2000.0 to 2999.9 acres, 3000 to 4999.9 acres, and 5000.0 acres or more.  | 1 to 9 head, 10 to 19 head, 20   to 49 head, 50 to 99 head, 100 to 199 head, 200 to 499 head, 500 or more   head, 500 to 999 head, 1,000 to 2,499 head, 2,500 or more head, 2,500 to   4,999 head, 5,000 or more head. |
| Market categories             | Total harvested acreage,   harvested acreage for fresh market, harvested acreage for processing   market.                                                                                                                                                                    | Not applicable.                                                                                                                                                                                                        |
| Number of farms               | Number of farms by state,   county, size, and market categories.                                                                                                                                                                                                             | Number of farms by state,   county, and size categories.                                                                                                                                                               |

## Imputed data:

Vegetable and cattle data are estimated using the model 3 and model 5, respectively, discussed in the manuscript of  
*Completing Under-Determined Spatial Agri-Food Data Systems: A Flexible  Bayesian Framework*. 


[Download Imputed vegetable data at the county-level](https://github.com/fedscornell/DataImputation/blob/main/Data/vegetables_enhanced.txt?raw=true)

[Download Imputed cattle data at the county-level](https://github.com/fedscornell/DataImputation/blob/main/Data/Cattle_enhanced.txt)

----------------------------------------------------------------------------------------------
## Acknowledgments:  
Special thanks to Dr. Quinton Baker, Jerzy Jaromczyk, and Chandler Zachary for their generous support, feedback, and  discussions. 


## Funding: 

This work was supported by the Cornell SC Johnson College of Business and Cooperative Agreement number 58-4000-8-0051 between Cornell University and the Economic Research Service of the U.S. Department of Agriculture. 


## Contact:
Please direct questions to jy348@cornell.edu.  