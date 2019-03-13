# Global Competitive Index by World Economic Forum Gapminder D3 based Data Vizualization

Hosted - https://rex17.github.io/GCI-WEF-D3-Data-Vizualization/

Description

Hans Rosling is a data visualisation legend. His 2006 TED talk, The Best Stats You’ve Ever Seen, is one of the most viewed videos on the TED website(http://bit.ly/2doLzAY). An updated interactive version of the GapMinder World visualisation used in that demo is available at www.gapminder.org/tools. This information visualisations is an homage to Hans Rosling.

In this created the a visualisation similar to the GapMinder World visualisation using d3.js. Visualisation is based on the World Economic  Forum  Global  Competitiveness  Report (http://reports.weforum.org/global-competitiveness-index-2017-2018/).
Visualisation features:
* A bubble plot representing the countries of the world
* Countries of the world described by GDP and Global Competitive Index mapped to x and y axis position
* The population of each country mapped to bubble area
* Appropriate labels and axes
* Appropriate use of colour
* Country name labels
* Ability to view data for a particular year
* Ability to animate the change in country statistics from year to year (2008 – 2017)

The data required to drive this visualisation is available in the folder data/GCI_CompleteData2.csv. The fields in this file are as follows:
* Country: The country name
* Year: The year for this data observation
* Population: The population of the country in this year
* GDP: Average GDP in inflation adjusted dollars
* 1st_pillar_Institutions
* 2nd_pillar_Infrastructure
* 3rd_pillar_Macroeconomic_environment
* 4th_pillar_Health_and_primary_education
* 5th_pillar_Higher_education_and_training
* 6th_pillar_Goods_market_efficiency
* 7th_pillar_Labor_market_efficiency
* 8th_pillar_Financial_market_development
* 9th_pillar_Technological_readiness
* 10th_pillar_Market_size
* 11th_pillar_Business_sophistication
* 12th_pillar_Innovation
* Global_Competitiveness_Index
* Income group : IMF defined ecnomoic group
* Region : The region in which the country belongs (similar to continent)
* Forum classification: Another region grouping
