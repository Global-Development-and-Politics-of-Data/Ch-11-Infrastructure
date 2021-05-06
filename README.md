# Ch-11-Infrastructure Data Module 2021-04-20

This is the repository for Chapter 11 - Infrastructure of the Data for Development Policy Research Project (PRP)

## Abstract
The primary purpose of our data module is to introduce textbook users to global infrastructure data. The following excercises highlight how infrastructure data is susceptible to the politics of data because infrastructure lacks a clear definition; can be interpreted at the regional, state, subnational, and city level; and sources a variety of data within weighted aggregate indexes. 

Users will learn how to manipulate, clean, analyze, and visualize data in Microsoft Excel. The module aims to teach users good data management practices when merging multiple datasets from sources that use varying methodologies. Users should understand the importance of matching data types and methodologies and will learn how to match primary keys for relational databases. The metadata behind the indicators also reveals whether the data is intended for top-down market oriented development purposes or if the indicator reflects a holistic, pro-poor approach. The module highlights how the choice of indicators and statistical weights may influence the analytical results of a single score composite index for a complicated issue area.

## Data Sources 
Since infrastructure is a very broad concept, we integrated multiple data sources, selecting specific indices or indicators related to the three subtopic areas: housing, ICT, and transportation. Other potential topics, such as  water and energy infrastructure, were not included to avoid excessive repetition or overlap with other textbook chapters, but could have been included.

[SDG Database](https://unstats.un.org/sdgs/indicators/database/)
  * Transport - 9.1.2 - Freight volume, by mode of transport (tonne kilometres or tkm)
  * ICT - 9.c.1 - Proportion of population covered by a mobile network, by technology
  * Housing - 11.1.1 - Proportion of urban population living in slums, informal settlements or inadequate housing
  * ICT - 17.8.1 - Proportion of individuals using the Internet

[UN Habitat Open Data](https://data.unhabitat.org/)
  * Housing - Basic Services Urban Indicators (Sufficient Living Area)
  * Transport - 11.2.1 - Proportion of population that has convenient access to public transport, by sex, age and persons with disabilities

[M49 Codes](https://unstats.un.org/unsd/methodology/m49/)

Downloaded: April 2021

---

**Metadata:** [SDG Metadata Repository](https://unstats.un.org/sdgs/metadata/), [UN Habitat 11.2.1](https://www.arcgis.com/sharing/rest/content/items/04c64cb5553843b8a644af6429b6633c/info/metadata/metadata.xml?format=default&output=html)

**[Zotero](https://www.zotero.org/groups/2509438/prp_2021_global_development/collections/ZHRBM6RD)**

## Organization
All of the files within this repository are Microsoft Excel workbooks. Some CSV files are included in the raw data folder for users who prefer to use an open-source platform such as R or Python.

1. Users should familiarize themselves with the metadata folder to understand the data collected.
2. Users should download the Merge-Start workbook and save their own version by adding initials and the date YYYY-MM-DD to the file name. Users should then copy sheets from the tidy-data folder. 
3. The raw-data folder could be used instead of the tidy-data documents for a more advanced merged and cleaning exercise. *Again, do not overwrite raw-data or tidy-data in the folders.* Examples how the module authors created the tidy-data files are under the cleaning-data folder.
4. The analysis folder includes the workbook used by authors to create the composite infrastructure index. Recreating the composite can be an advanced exercise for students seek to understand how to normalize data.
5. The FA-AK (will change to answer-key) folder includes the answer key workbooks for all the exercises. 
6. Each folder has its own README document with more information per workflow step.

## Exercises
* Exercise 1: Infrastructure Data “Mash-Up”;
* Exercise 2: Interpreting Infrastructure Indicators;
 * *optional advanced work - Calculating a composite score;*
* Exercise 3: Tipping the scales;
* Exercise 4: Visualizing Infrastructure Data and Mapping Regional Data.

For this exercise, you are expected to know a few Excel functions. Here is a list of the necessary arguments within the parentheses:

VLOOKUP - (value you are searching for, array where you are searching, column within the array to for the value, TRUE for close match or FALSE for exact match)
AGGREGATE (function [sum, average, median, count], what to do when you come across an error [select 6], array to base your calculations from) 
COUNTIF - (array where you are searching, what value/string you are searching for)
CONCAT - combines argument value 1 and value 2.

You can also find tutorials on Excel/Sheets on [Datacamp](https://www.datacamp.com/tracks/spreadsheet-fundamentals) or [Microsoft Office Support](https://support.microsoft.com/en-us/excel).

## License
[Open Science Framework (OSF)](https://osf.io/5e9j3/)

## Acknowledgements
Thank you to our colleagues in the [LBJ School](https://lbj.utexas.edu/)'s Data for Development PRP and our leaders: [Dr. Catherine Weaver](https://lbj.utexas.edu/weaver-catherine), [Dr. Ji Ma](https://lbj.utexas.edu/ma-ji), and Janet McLaren.
