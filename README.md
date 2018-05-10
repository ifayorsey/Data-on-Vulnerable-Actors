# StatesofExtraction


This past semester, I had the privilege of taking Manuela Picq’s States of Extraction class at Amherst College. More than once, I was shocked to discover the extent of transgressions many Latin American governments carry out on their own people, and additionally the lack of visibility and coverage surrounding these issues. When the opportunity came to carry out an intervention project, I was naturally excited to try and create a model that highlighted the plight of nature defenders. However I was quite alarmed at how little, and spread out data on the issue was. For my intervention project, I wanted to make information like this more accessible to statisticians and those alike who may not necessarily come in contact with such information, but can be useful agents in further bringing awareness to the issue.

The dataset I uploaded to Github contains 31 observations and 15 variables. Please feel free to download and use for your models! Descriptions of the variables are as follows:

* **country**: Country
* **region**	Region
* **sub.rgn**	Sub region
* **land.hct**	Country land area in hectares
* **icf**	Percent of indigenous and community lands acknowledged by govt
* **wpn.sld**	Revenue from weapons sold in USD
* **military.pct**	Percent of budget spent on military
* **corrupt.idx**	Corruption perception index from 2017
* **military.idx**	Military strength index
* **poverty.rt**	Poverty Rate
* **performance.idx**	Environmental Performance Index
* **defenders**	Number of human rights defenders killed in 2017
* **exports**	Revenue from exports  (Billion USD)
* **unemploy.rt**	Unemployment rate
* **crude.prd**	Crude oil production in 2017 (barrels per day)
* **refine.prd**	Refined oil producion in 2017 (barrels per day)



Sources of data include:


* https://www.cia.gov/library/publications/the-world-factbook/
* https://epi.envirocenter.yale.edu
* https://www.globalfirepower.com
* https://tradingeconomics.com
* https://www.frontlinedefenders.org/en/resource-publication/annual-report-human-rights-defenders-risk-2017


Most of the challenges in creating this intervention surrounded the creation of the dataset. Initially, I wanted to model what factors affected the number of defenders killed. Brazil, Colombia, Mexico, and the Phillipines however accounted for 80% of the nature defenders killed in 2017, and as such the variable showed no significant relationship with the others. Adding more countries only served to obscure this relationship by increasing the number of observations where defenders were not at risk. After reevaluating my expections, the next issue I came across was the consistency of some of the indexes. I frequently found myself crossing check some of these figures and often was unsure of which numbers where more accurate. Although these issues are present, they did not greatly impact the overall goal of increasing the visibility of this information. It is my hope that stats students interacting with this data leave with more insight into these issues, and with the knowledge that intervention and activism can take shape in many forms!