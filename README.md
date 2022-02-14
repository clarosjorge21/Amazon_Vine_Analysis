# Amazon_Vine_Analysis

### Overview 
Jennifer and I have been tasked with working on a larger project which analyzes review written by members of paid Amazon Vine program. We will be using PySpark to perform the ETL process and connect to a AWS RDS instance. From there we will load the transformed data into pgAdmin. By using PySpark we will determinate if there are any bias towards the favorable reviews from Vine Members in our dataset. 

### Results
![This is an image](https://github.com/clarosjorge21/Amazon_Vine_Analysis/blob/3d23e1adbc6a8bfcc448484256ff3e6d5dd7c943/bullet.1.PNG)

* There was a total of 613 Vine Reviews and a total of 64,934 non-Vine reviews.
* Out of the 613 Vine reviews there was a total of 222 5 star reviews. Out of the 64,934 non-Vine reviews there was a total of 30,530 total 5 star reviews.
* 36.21% of the vine reviews were 5 stars. 47.02% of the non-vine reviews were 5 stars.

### Summary
Based on the results, Vine members did not show any bias when they were rating the products. There is only roughly about a 10% difference between the two. You can assume that Vine customers are important due to our analysis. We should include additional information if we were to keep trying to filter through the information to help solidify our assumptions. 

One additional analysis that could be done to help the dataset is by using the same time of analysis but with a different dataset. This could show whether or not the reviews made by the Vine members are bias. 
