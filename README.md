# data-mining-homework
各聚类算法在两个数据集下的运行数据如下：
kmeans_digits:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI		silhouette
k-means 0.33s	0.602	0.650	0.625	 0.465	0.621	 0.144
_______________________________________PCA________________________________________
K—means 0.03s	0.643	0.682	0.662	0.532	  0.659 	0.272
__________________________________________________________________________________
kemean_doc:
init		time	homo	compl	v-meas	ARI		AMI
k-means 18.57s	0.548	0.293	0.382	0.185	0.379
_______________________________________PCA________________________________________
K—means 0.04s	0.580	0.301	0.396	0.222	0.394
__________________________________________________________________________________

Affinity Propagation_digits:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI		silhouette
Affinity 4.86s	0.932	0.460	0.616	0.154	 0.573	 0.105
_______________________________________PCA________________________________________
Affinity 4.35s	0.869	0.473	0.612	0.198 	0.584	 0.150
__________________________________________________________________________________

Affinity Propagation_doc:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI
Affinity 13.99s	0.822	0.186	0.303	0.011	0.247
_______________________________________PCA________________________________________
Affinity 12.21s	0.689	0.211	0.323	0.051	0.309
__________________________________________________________________________________

SpectralClustering_digits:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI		silhouette
SpC     0.84s	0.805	0.853	0.828	0.707	 0.826	  0.138
_______________________________________PCA________________________________________
SpC     0.45s	0.740	0.782	0.760	0.613 	0.758  	0.250
__________________________________________________________________________________

SpectralClustering_doc:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI
SpC     49.60s 0.564	0.346	0.429	0.381	0.426
_______________________________________PCA________________________________________
SpC      1.96s	0.494	0.307	0.378	0.200	0.375
__________________________________________________________________________________

AgglomerativeClustering_digits:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI		silhouette
AgC     0.30s	0.758	0.836	0.796 0.664	 0.793	  0.125
_______________________________________PCA________________________________________
AgC     0.14s	0.649	0.719	0.682	0.492 	0.679  	0.237
__________________________________________________________________________________
AgglomerativeClustering_doc:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI
AgC     10.60s	0.473	0.301	0.368	0.311	0.365
_______________________________________PCA________________________________________
AgC     0.47s	0.578	0.297	0.392	 0.230	0.390
__________________________________________________________________________________

GaussianMixture_digits:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI		silhouette
GaM     0.76s	0.647	0.695	0.670	0.505	 0.667	  0.126
_______________________________________PCA________________________________________
GaM     0.17s	0.658	0.697	0.677	0.511 	0.674  	0.237
__________________________________________________________________________________
GaussianMixture_doc:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI
GaM     64.94s	0.470	0.327	0.386	0.265	0.384
_______________________________________PCA________________________________________
GaM     0.56s	0.500	0.322	0.391	0.304	0.390
__________________________________________________________________________________

mean_shift_digits:
__
init		time	homo	compl	v-meas	ARI		AMI		silhouette
mean_shift	0.24s	0.009	0.257	0.017	0.000	0.006	0.329
_______________________________________PCA________________________________________
mean_shift	0.29s	0.003	0.215	0.005	0.000	0.000	0.530
__________________________________________________________________________________
mean_shift_doc:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI
mean_shift	11.04s	0.000	1.000	0.000	0.000	0.000
_______________________________________PCA________________________________________
mean_shift	0.04s	0.000	1.000	0.000	0.000	0.000
__________________________________________________________________________________

DBSCAN_digits:
__
init		time	homo	compl	v-meas	ARI		AMI		silhouette
DBSCAN 	0.46s	0.005	0.182	0.010	0.000	 0.002  	0.331
_______________________________________PCA________________________________________
DBSCAN  0.17s	0.001	0.163	0.002	0.000 	0.000	  0.709
__________________________________________________________________________________
DBSCAN_doc:
__________________________________________________________________________________
init		time	homo	compl	v-meas	ARI		AMI
DBSCAN  0.64s	0.000	1.000	0.000	0.000	0.000
_______________________________________PCA________________________________________
DBSCAN  0.13s	0.000	1.000	0.000	0.000	0.000
__________________________________________________________________________________



