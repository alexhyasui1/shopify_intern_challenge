# shopify_intern_challenge
Shopify Summer 2022 Data Science Intern Challenge

## Observations
### AOV Analysis
* After calculating for the average price of sneakers at each shop and then averaging the price of all single order sneakers, we noticed that the AOV still seems higher than it should be.
* Store 78 as a result was the cause of a higher AOV selling each pair of sneakers at $25725.00.

### Re-Evaluating the AOV
* Discovered another anomaly where a store was selling 2000 items per order.
* Unfortunately consumer spending is an uncontrollable factor therefore store 42 is considered to be removed from the data to receive a reasonable AOV.

### New Metric
* Z-score is used to confirm whether if store 78 and 42 were anomalies. 
* We noticed that all other stores recorded a Z-score of less than 0.1 except store 78 and 42 which indicates that its values are far from the mean. 
