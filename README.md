# Amazon_Vine_Analysis
## Overview
This project is designed to search through the reviews from the automotive section of amazon to determine if there is any bias in the number of stars given vs if the review was paid/unpaid.
</br>
The data is filtered before it undergoes analysis:
- The data is filtered to only include reviews with 20 or more votes.
- The data is then filtered to only include 50% and above for helpful votes.
- The data was then separated into:
    - Paid reviews
    - Unpaid reviews

Three determinations were then drawn about the data.
- How many reviews exist in each category?
- How many reviews were 5 star?
- What percentage of the 5 star reviews are paid vs unpaid?

See fig. 1, 2
![](images/1.png)
![](images/2.png)

## Summary
A somewhat surprising conclusion is drawn when assessing the results of the data filtering. In fig. 1 we can see the filtering process begin and put our data size into perspective. We can then begin to assess paid vs unpaid reviews in fig. 2 below. The number of paid 5 star reviews is outnumbered by unpaid 5 star reviews by a factor of nearly 300:1. An overwelming number of unpaid reviews are 5 stars and make up 51.9% of the total unpaid population. Of the 43 paid reviews, only 14 were 5 star comprising 32.6% of the total paid population.