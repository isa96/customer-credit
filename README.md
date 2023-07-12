# Customer Credit Card Clustering

This project aims to built a *clustering* model on *credit card* customers and evaluate the *behavior (characteristics)* of each *cluster* with 
ultimate goal  meet *customer* needs for targeted *clusters*


# Brief Summary of Project

The flow of this *project*, first EDA (*Exploratory Data Analysis*) to find out the basic picture of the *dataset*. 
Then *cleaning* and *preprocessing* of the *dataset*. Second, I performed PCA to reduce the dimensionality of the data and 
reduce the possibility of overfit. Third, I performed clustering using K-Means Nearest Neighbor. 
Result of clustering, there are 5 customer clusters with specific characteristics

# Project Conclusion

1. **Cluster 0 (Frugal customer type)**

    *Customers* in this *cluster* tend to make purchases as needed, because *customers* rarely make purchases. 
	In addition, this *cluster* has a low *credit limit* so, *value payment* made by the *customer* is also low. 
	However, this *cluster* often makes *update balance* on his *credit card*. 


2. **Cluster 1 (The type of customer who has a low economy so they often use the installment method)**

    This *customer* in this *cluster* has a lower *balance* than the other *cluster*. 
	Therefore, this *customer* often makes purchases using the *Installment* method. The low *balance* also causes this *cluster*, 
	have a lower *value* of purchases on the *Cash Advance* method. Because there are many installments (due to the *installment method*), 
	this *cluster* has higher *payment* percentage than other *customers*. 

3. **Cluster 2 (High economic customer type)**

    *Customers* in this *cluster* have a higher purchase *value* than other *clusters*. 
	This is because *cluster* have higher *credit limit* than other *clusters*. Because of frequent purchases, the number of *payments* from 
	this *cluster* is higher than the other *cluster*. The method that this *cluster* often uses is *One Off Purchases* (more often than other *cluster*). 
	This *cluster* has the highest *value purchases* in this method. This *cluster* also does *update balance* frequently.

4. **Cluster 3 (The type of customer who aims for quality goods)**

    This *customer* has the highest *balance* among other *clusters*. Therefore, this *cluster* often makes purchases using 
	the *Cash Advance* method rather than the *Installment Purchases* method. Despite having a high *balance*, *customers* in this *cluster* 
	make the least frequent purchases (A type of *customer* who aims for quality, because they rarely buy but when they do, the *value* is high). 
	In addition, *cluster* also often make *update balance*.

5. **Cluster 4 (The type of customer who prefers to use the Cash method)**

    *Customers* in this *cluster*, have a lower purchase *value* among other *cluster*. This *cluster* also rarely makes purchases using 
	the *Installment Purchases* and *One Off Purchases* methods. This *cluster* tends to use the *Cash Advance* method. 
	This *cluster* is also the least likely to update its *balance* of all *cluster*.