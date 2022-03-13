# WFP-Rwanda
## 1) Introduction
In this analysis report, I am using the dataset which contains Food Prices data for Rwanda, sourced from the World Food Programme Price Database. 
The database covers food prices such as maize, rice, beans, fish, and sugar in Rwanda and contains to monthly data from 2000 to 2022. 

Since the 1994 genocide, Rwanda has recorded significant achievements in poverty reduction and food production; however, 38.2 percent of the population still live below the poverty line and almost one fifth is food insecure. The situation is further aggravated by the presence of over 175,000 Congolese and Burundian refugees (as of January 2019), 91 percent of whom reside in refugee camps and the remaining 9 percent in urban areas. Thus, having general understanding of food prices data is necessary. In this report, I made visualizations to help readers understand the dataset more easily.

## 2) Data Source
HUMANITARIAN DATA EXCHANGE
https://data.humdata.org/dataset/wfp-food-prices-for-rwanda

The Humanitarian Data Exchange (HDX) is an open platform for sharing data across crises and organisations. HDX is managed by OCHA's Centre for Humanitarian Data and the OCHA is part of the United Nations Secretariat that is responsible for bringing together humanitarian actors to ensure a coherent response to emergencies.

## 3) Research Questions
Is there any regional difference in food prices in Rwanda?
Is the food prices in Rwanda highly-volatile?
Is the food supply-chain in Rwanda well-established?

## 4) Packags I imported:
install.packages("treemap", type="binary")
install.packages("forecast", type="binary")
install.packages("fpp2")
install.packages("scales")
install.packages("ggfortify")
install.packages("zoo")
