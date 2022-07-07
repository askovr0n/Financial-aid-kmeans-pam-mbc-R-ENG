# Which countries should receive financial aid first?

- Dataset contains information about socio-economic and health factors for 167 countries
- The work uses unsupervised learning method based on clustering: Kmeans, PAM, Hierarchical Clustering and Model Based Clustering
- The Hopkins metric (if dataset has "clustering" characteristics) was used for prediagnostic purposes, while the Sillhoutte and GAP method was used to select the optimal number of clusters
- The paper considers that minimising the variables import, export, income and maximising the variable inflation rate, defines the countries that appear to be the poorest
- The analysis shows that we should divide countries into 3 categories in terms of wealth, where the poorest group of countries mostly included countries from Africa. Therefore, the results of the analysis were considered to be in line with reality
- R software was used for data mining, engineering and modelling. Additionaly, the paper has been published on the [Rpubs website](https://rpubs.com/askovron/financial-aid-clustering)

Snapshot of EDA          |  Clustering - KMeans/PAM
:-------------------------:|:-------------------------:
![](https://github.com/askovr0n/Portfolio/blob/main/images/Project_3/EDA.png)  |  ![](https://github.com/askovr0n/Portfolio/blob/main/images/Project_3/clusters.png)
