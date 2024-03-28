# Product-Recommendation-System
This system generate a personalized list of recommended products for each user. 

1.	Begin by importing and visualizing the dataset. Organize the data into a 2D matrix format, utilizing User ID (UID) and Product ID as the basis for recording user interactions.
2.	Computed the features for each user. In this context, features represent the count of distinct products purchased by each user.
3.	Employ a nearest neighbor algorithm to identify the five closest neighbors for each user. These neighbors will be chosen based on similarity in product purchase behavior.
4.	Combine the products purchased by the current user and their five nearest neighbors (including the user itself). This forms a union of products collectively bought by this group.
5.	Implemented the process of systematically identifying nearest neighbors and aggregating purchased products for each user. This will result in the creation of a recommendation database tailored to individual users.
