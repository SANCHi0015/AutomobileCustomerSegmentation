# AutomobileCustomerSegmentation

Customer segmentation for Automobiles reward program members on the basis of their spending score, to further assist marketing team design marketing strategies accordingly.

# ML Techniques used : K-Means, PCA, t-SNE, Gaussian Mixture Models, Silhouette plot, SSE/Inertia, Cluster Analysis
# Project Domains : Market Segmentation, Marketing, Data Science, Cluster Analysis

Q Why segment customers? 
Ans - Well, because it is still a very difficult and computationally intensive task to target each customer in unique ways, as well as there would be lots of customers on which similar Marketing strategies and Discount offers would work well. Hence it makes intutive sense to break the customer base into clusters on the basis of how and which offers they react to and then proceed to make targeted strategies.

# About this project -
Performed Data Engineering to merge the 3 datasets, performed Data Cleaning (Some enteries were errors cause their data was missing as well as age was 118 which seemed to be an error). (coe == customer offer engagement) image

Used Power Transforms to make dataset more gaussian since K-means likes rounder (isotropic) clusters.

Performed PCA ( Principal Component Analysis ) to reduce Data Dimensionality and avoid Curse of Dimensionality , and also so that redundant features would be removed and the data would be in continuous so that we don't need to bother ourselves with K-Prototype kind of algorithms ( its K-means plus K-mode for mixed (continuous plus categorical) data modelling )
