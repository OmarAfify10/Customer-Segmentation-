# Customer-Segmentation-(Kmeans)
In this Project we work witha dataset which contains information about the Price , the quantity and type of the products. We used these information to get some useful insights to improve the E-commerce business .We used K means to identify many types of customers and customer behaviour , which could be extremely useful for providing suitable solutions and offers for the customers .

# Binder Badge
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OmarAfify10/Customer-Segmentation-/HEAD)

# Execution 
Use the binder link above to run the Customer.Seg.ipynb .

# Results
we made 3 Clusters (Customer ID , Unit Price ,Quantity) and used these clusters to know more information about each country .

#Cluster 0 contains the majority of orders (378366 out of 541909), where the average Quantity value is at 10, and the average UnitPrice value is at 5.38. The median values of both variables are below the average values. This may indicate that most orders consist of a small number of items with a relatively high price.

#Cluster 1 also contains a significant number of orders (163539 out of 541909). In this cluster, the average value of Quantity is slightly higher than in cluster 0, and is 12, and the average value of UnitPrice is 2.84. The median values of both variables are also lower than the average values. This may indicate that most orders in this cluster contain a higher quantity of goods, but with a lower price.

#Cluster 2 contains only 4 orders, which makes it less significant for analysis. However, it can be noticed that the average value of Quantity in this cluster is at an extremely high level (77605), which is an outlier relative to the rest of the data. The average UnitPrice value in this cluster is at 1.56.

