## Based on markdown promotions, Are stores improving their Quarterly sales from the same period last year ?

#### The data used for this research was part of a Kaggle Dataset and Competition sponsored by Walmart Corporation
```
https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting
```

##### What's in our dataset ?

The dataset includes total sales for 45 Walmart Locations broken down by store department.  For each store, you will know the type and size (in sqft).  When available, up to 5  markdowns figures (promotion/discounts) used at each store are provided.  Please note that identifiable information regarding the locations fo a store and the nature of the discounts have been removed.  We will limit our analysis to periods where a store provides at least some markdown data.  

##### Hypothesis  

```
Each store-group has not improved it's Quarterly saless with markdowns over the same Quarter from one year ago
```

##### Rollout Plan (show how you would implement and execute the experiment)


On a weekly basis:

Collect Sample data:
1. Each store will Record up to 5 promotions at each store and markdown-value (in Dollars)
1. Each store will Record sales in each department
1. For the control group, use Quarterly Periods in 2011
1. For the test group, use Quarterly Periods in 2012

##### Evaluation Plan (Analysis that highlights your experimental hypothesis)

1. Control groups: Aggregate (2011) into 3 segments (by sizes: < 100, sqft, between 100,000 and 200,000, and greater than 200,000)
1. Test groups: Aggregate (2012) into 3 segments (by sizes: < 100, sqft, between 100,000 and 200,000, and greater than 200,000)
1. Calculate T-Values between control & test groups
1. Determine if P-Value meets 5% threshold to reject NULL Hypotheses

##### AdditionalQuestions to answer:

1.  How did markdown/promotions affect store sales with respect to size ?
    ```
    smaller than 100,000 SQFT
    between 100,000 & 200,000 SQFT
    larger than 200,000 SQFT
    ```
1. How did markdown/promotions affect intra-quarter sales ?

