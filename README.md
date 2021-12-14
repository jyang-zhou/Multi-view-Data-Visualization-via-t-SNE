# Multi-view Data Visualization via t-SNE

mSNE and multi-SNE are implemented on different types of data, where mSne and multi-SNE are two different methods to visualize multi-view data. 

Please see sample code for more detail

Visualization and Accuracy

![image](https://user-images.githubusercontent.com/95513386/145927961-a8278201-8c83-4ff0-b228-d250f0e3b3c8.png)

![image](https://user-images.githubusercontent.com/95513386/145927976-c56dd96c-4767-4cb5-858f-5e10db5d315c.png)

![image](https://user-images.githubusercontent.com/95513386/145927987-077f7cac-9c4a-4800-8d24-49d24f655ba8.png)

![image](https://user-images.githubusercontent.com/95513386/145928001-e81d78c3-a880-48d3-b044-acbd3226489a.png)

![image](https://user-images.githubusercontent.com/95513386/145928017-21e57f94-677c-4876-bbb6-8964f41251fc.png)

Evaluation	Method		"Handwritten Digits
(Multi-view)"	"Handwritten Digits
(Single-view\2groups)"	Cancer Type	"Images
Caltech-7"	Noisy Handwritten Digits
"Accuracy
 (ACC) 
(how many have been classifed correctly)"	t-SNE		0.7335	0.7	0.3574	0.8263	0.369
	multi-SNE	PCA	0.752	0.9	0.4355	0.8787	0.3595
		ISOMAP	0.85	0.878	0.4414	0.8508	0.735
		UMAP	0.8405	0.8015	0.3784	0.8691	0.623
	m-SNE	PCA	0.603	0.8265	0.3874	0.8358	0.386
		ISOMAP	0.642	0.833	0.3724	0.8365	0.4185
		UMAP	0.734	0.764	0.3694	0.8365	0.3805
"Nomalised Mutual Information
(NMI)
(how much information can be obtained from one to the other)"	t-SNE		0.6741	0.6653	0.0394	0.5707	0.4092
	multi-SNE	PCA	0.752	0.8141	0.0273	0.759	0.3447
		ISOMAP	0.8537	0.7753	0.0261	0.6484	0.6277
		UMAP	0.8259	0.6658	0.0323	0.7085	0.5394
	m-SNE	PCA	0.7429	0.7429	0.01	0.6024	0.397
		ISOMAP	0.7026	0.7407	0.00123	0.6161	0.4203
		UMAP	0.7753	0.6594	0.0062	0.6063	0.3978
"Rand Index
(RI)
(similarities between clustering data)"	t-SNE		0.9133	0.9121	0.5195	0.7893	0.8286
	multi-SNE	PCA	0.9329	0.9632	0.5164	0.9257	0.8156
		ISOMAP	0.9602	0.9548	0.51	0.8725	0.9167
		UMAP	0.9512	0.931	0.5527	0.9023	0.892
	m-SNE	PCA	0.8912	0.9427	0.3469	0.8133	0.8265
		ISOMAP	0.903	0.9449	0.347	0.8126	0.8404
		UMAP	0.9337	0.9243	0.3352	0.8151	0.822
"Adjusted Rand Index
(ARI)"	t-SNE		0.5449	0.546	0.0253	0.6038	0.2576
	multi-SNE	PCA	0.6484	0.796	0.0204	0.8485	0.2026
		ISOMAP	0.7896	0.7497	0.0222	0.7444	0.5511
		UMAP	0.7367	0.6198	0.026	0.8026	0.4348
	m-SNE	PCA	0.5988	0.6857	0.00027	0.6379	0.252
		ISOMAP	0.5417	0.6971	0.00034	0.637	0.2727
		UMAP	0.66	0.5913	0.00036	0.6414	0.2295![image](https://user-images.githubusercontent.com/95513386/145928145-e3214966-03c1-42cc-a011-3fcd922346d0.png)



