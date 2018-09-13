# Access Ethereum Blockchain Data with SQL 

Google just announced import of the Ethereum blockchain into its BigQuery service on a daily basis. As a huge **blockchain** and Ethereum fan, this could not have been more timely. Over the past months Ethereum has seen massive price drops and the decision by google to build a service around Ethereum is probably the only recent good thing happening to the platform.

Google BigQuery is a cloud-based big data analytics web service for processing very large read-only data sets [More ...](https://searchdatamanagement.techtarget.com/definition/Google-BigQuery)

The Ethereum Blockchain is not the first to be imported by Google. The **Bitcoin** blockchain was recently pulled too. 

## What that means for you and I 

The first and most glaring advantage of this is that developers no longer need to interact with a blockchain to get useful data and conduct analysis. Take a look at how you can uery the token balance for a particular address 

![Image of Query](https://cdn-images-1.medium.com/max/1000/1*9j8csoKZtRD2ffFfzm3OPA.png)

Other possibilities for Ethereum blockchain analysis include 
* visualization of smart contracts
* speed given that it runs on **Google Cloud Storage** infrastructure
* diagramatic analsis of all Ethereum transfers and aggregated transaction cost

However, it is worth noting that you need to create a project before you can use BigQuery for free. You pay $5 per 1TB of data processed but your first 1TB has no charges. Google Cloud Platform also gives you $300 credit so you can query 60TB of data for free even after you exceeded 1TB limit.

Thanks for reading !

Official Statement - [Here] (https://cloud.google.com/blog/products/data-analytics/ethereum-bigquery-public-dataset-smart-contract-analytics)
