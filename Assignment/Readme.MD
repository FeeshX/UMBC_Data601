## **The Housing Market During the COVID-19 Pandemic**
**Exploratory Analysis**

The analysis looks at the developments in the housing market during the period January 2017 - August 2020 in the U.S in terms of pricing, inventory and sales, as provided and defined by Redfin, a national real estate brokerage. The local data is grouped by metropolitan area and by county; overall it provides housing data on 1527 Counties. 

**Navigating this Repo**
---
* [Dataset](https://github.com/FeeshX/UMBC_Data601/blob/master/Assignment/Code/Housing_Analysis.ipynb) Raw .xlxs file. Retrived from the following link on 9/17/20: https://www.redfin.com/blog/data-center/
* [Notebook](https://github.com/FeeshX/UMBC_Data601/blob/master/Assignment/Code/Housing_Analysis.ipynb) Jupyter notebook used to clean, organize and analyze data.
* [Readme](https://github.com/FeeshX/UMBC_Data601/edit/master/Assignment/Readme.MD) An overview of the dataset, method and summary of analysis. 

**Method**
---
I initally converted the file from TSV to CSV for ease of analysis. Tab Separated Values (TSV)and Comma Separated Values (CSV) are the two file type extensions used to load a set of data. A .tsv file will have tab separated values whereas .csv file has comma separated fields. I narrowed down the available variables (columns) in the dataset to study the impact of the pandemic on three key areas: 1) Total Homes Sold 2) Inventory (number of homes on the market) and 3) Homes delisted. To assess whether Covid-19 affected numbers in these areas, I used data from 2017-2019 as comparision for the current year 2020. The initial dataset was collected on either a rolling 1, 4 or 12-week window. I scaled down my dataset to show numbers for a 1 week window, as it would better reflect any marginal changes in the housing market and provide a clearer picture.

**Summary**
---
My analysis shows that COVID-19 has impacted the U.S. housing market. As the pandemic starting spreading in mid-March, on the demand side, homebuyers may have been hesitant to visit prospective homes due to stay-at-home orders.

![Image of Homes Inventory](https://github.com/FeeshX/UMBC_Data601/blob/master/Assignment/Images/Homes_inventory.PNG)

On the supply-side, the inventory of homes decreased by 21.7% between March 2020 to April 2020 and the number of delistings increased by 39.1% as sellers may have delisted their homes to prevent the risk of contracting the disease. 

![Image of Homes Delisted](https://github.com/FeeshX/UMBC_Data601/blob/master/Assignment/Images/Homes_delisted_YYYY_MM.PNG)

The rebound in home sales is being led by mortgage interest rates, which hit an all-time low in August. The 30-year fixed mortgage rate is at an average of 2.98%, the lowest since 1971, according to data from Freddie Mac.

![Image of Total Homes Sold](https://github.com/FeeshX/UMBC_Data601/blob/master/Assignment/Images/Total_homes_sold_YYYY_MM.PNG)

My findings are corroborated by this [Reuters Article](https://www.reuters.com/article/us-usa-economy-housing/u-s-home-sales-rack-up-record-gain-tight-supply-covid-19-seen-slowing-momentum-idUSKCN24N22B), pointing out that "U.S. home sales increased by the most on record in June, boosted by historically low mortgage rates, but the outlook for the housing market is being clouded by low inventory and high unemployment amid the COVID-19 pandemic". This combination means that in most Counties, potential buyers are bidding on a limited supply of homes for sale.
