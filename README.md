## INTRODUCTION

This project aims to classify the 89 customers of a specific company using the K-Means algorithm, a machine learning clustering method. From the database, we will use only two spreadsheets: “orders.csv” and “order_details.csv”. With these, we will apply the RFM (Recency, Frequency, and Monetary) method.


## **THE RFM METHOD:**

**Recency –** Indicates when the last order was made by each customer.

**Frequency –** Indicates how many times the customer has purchased from the company.

**Monetary –** Indicates the average ticket price of the customer’s orders.

Using the values from these three categories for each customer, we standardize the data and apply the K-Means algorithm to classify them into four different groups:


## **K-MEANS ALGORITHM:**
The K-Means algorithm is a popular clustering method used in machine learning. It aims to partition n observations into k clusters, where each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster.


## **STEPS OF K-MEANS:**

**Initialization:** Select k initial centroids randomly.

**Assignment:** Assign each data point to the nearest centroid, forming k clusters.

**Update:** Calculate the new centroids as the mean of the data points in each cluster.

**Repeat:** Repeat the assignment and update steps until the centroids no longer change or change minimally.

K-Means is useful for segmenting customers into distinct groups based on their purchasing behavior, which can help in targeted marketing and improving customer satisfaction.


## **RESULTS:**
**Premium Customer (Clientes Premium):** These customers have purchased within the last month, have a high purchase frequency, and an extremely high average ticket value. They are extremely valuable to the company and should be constantly monitored to ensure their continued satisfaction with the company's services.

**Very Good Customer (Clientes Muito Bons):** These customers last purchased between 1 and 2 months ago, buy frequently, and have a high average ticket value. They are also valuable customers who require constant monitoring. The main difference compared to Premium customers is the average ticket value.

**Good Customer (Clientes Bons):** These customers last purchased between 2 and 3 months ago, buy with reasonable frequency, and have a reasonable average ticket value. These customers demand attention but are not a priority for the company.

**Possible Churn (Possível Churn):** These customers have purchased at most once or twice a long time ago and have a very low average ticket value. They are highly likely to abandon the company and should be contacted by phone and through marketing campaigns to try to re-engage them.

![Customer Classification Result.png](https://github.com/lucassigoli/Machine-Learning-Churn-Analysis-Clusterization/blob/main/Customer%20Classification%20Result.png)

**REFERENCE:** https://www.linkedin.com/pulse/an%C3%A1lise-rfv-com-python-clusteriza%C3%A7%C3%A3o-de-clientes-machine-lima--ewmzf/
