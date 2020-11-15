# Mall-Segmentation
# Abstract
This project is an unsupervised learning problem. I will be making use of clustering. It is a type of unsupervised learning method and a common technique for statistical data analysis used in many fields. Clustering mainly is a task of dividing the set of observations into subsets, called clusters, in such a way that observations in the same cluster are similar in one sense and they are dissimilar to the observations in other clusters. In simple words, we can say that the main goal of clustering is to group the data on the basis of similarity and dissimilarity.
# Introduction
The clustering algorithm I will make use of is KMean clustering algorithm
KMean clustering algorithm is one of the well known algorithm for clustering data. Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while also keeping the clusters as different (far) as possible
# Problem Statement
I own a super market and through a membership card, I have some basic data about my customers like CustomersID, age, gender, annual incmome and spending score. I want to understand the customers so that I will have a sense about what each customer is interested in and how I will be able to target them
# Business goal
My goal is to perform customer segmentation. Customer segmentation is the activity of dividing a broad consumer or business market, normally consisting of existing and potential customers, into sub-groups of consumers based on some type of shared characteristics. I hope to gain a deeper understanding of our customers preferences and to discover what each sub group or cluster finds most valuable to them
# Data Source
The data is publicly availabel on the kaggle website
# Model:: Unsupervised learning using Kmean Clsutering
# Looking at the first five rows of my data customers,csv
![Capture41](https://user-images.githubusercontent.com/74493164/99184821-c05b4180-2713-11eb-9afe-99f175798071.PNG)
# Data Visualization
This involves understanding my dataset by placing it in a visual context so that patterns, trends and correlations that might not notherwise be detected can be exposed
## Pairplot

![Capture42](https://user-images.githubusercontent.com/74493164/99184913-8179bb80-2714-11eb-9774-77fd7f729a81.PNG)
# Clustering
## 2D clustering based on Age and spending score(1-100)
## Using elbow rule to determine k

![Capture43](https://user-images.githubusercontent.com/74493164/99185047-3ca25480-2715-11eb-9568-dfdc271ed869.PNG)
## K = 4

![Capture46](https://user-images.githubusercontent.com/74493164/99185132-e255c380-2715-11eb-984c-e5cd3f267f80.PNG)

# 2D Clustering based on Annual income and spending score

## using elbow rule to determnine k

![Capture47](https://user-images.githubusercontent.com/74493164/99185208-6445ec80-2716-11eb-9349-12634753daae.PNG)

## k= 5

![Capture48](https://user-images.githubusercontent.com/74493164/99185268-ad963c00-2716-11eb-8e07-f1a87f38e4c1.PNG)

# 3D Clustering based on Age, Annual income and Spending score

## Using elbow rule to determine k

![Capture49](https://user-images.githubusercontent.com/74493164/99185356-3dd48100-2717-11eb-8836-999b49d081d9.PNG)
 ## k=6
 
 ![Capture50](https://user-images.githubusercontent.com/74493164/99185374-72483d00-2717-11eb-85f8-83ba5982342f.PNG)
 
 ## Conclusion
I have analysed Customer data and performed 2D and 3D clustering using K Means Algorithm. This kind of cluster analysis helps design better customer acquisition strategies and helps in business growth.
