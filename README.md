# Customer segmentation and analysis

This is a project for making customer segmentation through clusterization algorithms and analysis on a dataset from Kaggle (https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis).

Inside `customer_segmentation_and_analysis.ipynb` you can find:

- EDA.
- Data Cleaning.
- Feature Engineering.
- PCA with 2, 3, 4 and 5 components.
- Different algorithms: K-Means, Agglomerative Clustering, DBSCAN.
- Evaluation and profiling of the clusters found.

The model which performed best was K-Means with a Silhouette score of 50% on the data after applying dimensionality reduction with PCA of 2 components:

!["Data after applying PCA with 2 components"](imgs/pca2.png?raw=true "Data after applying PCA with 2 components")
!["Data after K-Means clustering"](imgs/clusters_pca2.png?raw=true "Data after K-Means clustering")


Insights among all clusters:
-	Similar distributions on number of days since last purchase.
-	Almost nobody complained in the last 2 years.
-	Similar proportion between having a partner (≈65%) and not having.

Cluster 0:

-	On average, this is the group with least Income.
-	≈70% have a kid at home, ≈25% don’t.
-	Could have a teenager at home (≈59%) or not (≈40%).
-	Most of them are parents (≈90% are, ≈10% are not).
-	On average, least purchases made from every origin between all groups.
-	On average, this is the group with more website visits in “the last month” (only a few more).
-	Least group to accept in Campaign 4.
-	Most of them were born between the 60’s and 80’s (≈80%).
-	They are the group that least spent.
-	They are the group that least accepted an offer in any campaign. Only ≈15%.
-	≈65% of them are with a partner, ≈35% are not.  
-	Among all products categories, most customers in this group individually choose wine to spend the most (≈55% of them). Also, they are the only group which its customers could spend the most on fruits, sweet, fish and gold products compared to the other groups.
-	Among all products categories, this is the only group that has customers who could choose wine to spent the least.
-	On average, they as a group spend the least on every product category compared to the other groups.

Cluster 1:

-	On average, this is the group with most Income.
-	Most of them are not parents (≈97%).
-	On average, this group is the least which made purchases with a discount.
-	On average, this group tops on purchases made using a catalog.
-	On average, is the group with least website visits in “the last month”.
-	This group is the only one which has more customers who are prone to accept an offer of any campaign (≈60%). Also, this group leads on accepted offers on all the campaigns.
-	On average, this group is the one which spent the most in every category of products and in total.
-	≈60% of them are with a partner.  
-	Among all products categories, most customers in this group individually choose wine to spend the most (≈ 65%) and meat in second place (≈ 34%).
-	Among all products categories, most customers in this group individually could choose every category of product to spend the least, except for meat and wine.
-	On average, they as a group are in 2nd place in terms of amount spent on every product category compared to the other groups.


Cluster 2:

-	On average, this groups falls between the group that has more Income and the group that has less.
-	Only ≈20% have a kid at home, while ≈79% don’t.
-	Most of them have a teenager at home (≈85%), some don’t (≈10%).
-	Most of them are parents (≈95% are, ≈5% are not).
-	On average, this group tops on purchases with a discount.
-	On average, this group tops on purchases made through the website.
-	Most of them were born between the 50’s and 70’s (≈90%).
-	On average, this group is in 2nd place in terms of total amount spent.
-	Most of them haven’t accepted an offer from any campaign (≈79%).
-	≈69% of them are with a partner.  
-	On average, most people on this group enrolled slightly earlier in time than people from the other groups.
-	On average, this group leads in total number of purchases made from every origin, but it’s near to the Group 2.
-	Among all products categories, most customers in this group individually choose wine to spend the most (≈ 90%) and meat in second place (≈ 7%). Also, they lead between all groups to choose wine to spend the most compared to all product categories.
-	Among all products categories, most customers in this group individually could choose every category of product to spend the least, except for meat and wine.
-	On average, they as a group are in 2nd place in terms of spending on every product category compared to the other groups.
