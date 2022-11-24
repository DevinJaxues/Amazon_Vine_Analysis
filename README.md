# Amazon_Vine_Analysis
## Devin Monsen
### 08/31/2022
---
## Overview of the Pewlett Vine Analysis ##
---
In this analysis we took a dataset from a set of databases from Amazon's AWS. We then performed the ETL process. Loading the dataset into an AWS server. Connecting that AWS to PGAdmin. Extracting the data in a ipynb file. Transforming the dataset into multiple dataframes using PySpark. And extracting statistics from those dataframes. Lastly, loading our new dataframes into tables in PGAdmin using our Spark server.
---
## Results ##
---
- Vine reviews
---
![totalpaid](images/totalpaid.JPG)
![paid5](images/paid5star.JPG)
![paidpercent](images/paidpercent.JPG)
---
- Non Vine reviews
---
![totalunpaid](images/totalunpaid.JPG)
![unpaid5](images/unpaid5star.JPG)
![unpaidpercent](images/unpaidpercent.JPG)
---
## Summary ##
---
In conclusion, we can see that 51% of the Vine reviews are 5 star reviews. Where in contrast the unpaid reviews only had 38% of 5 star reviews. This tells us that the program is a net positive for the overall reviews by a difference of 13%.
