# Multi-view Data Visualization via t-SNE

mSNE and multi-SNE are implemented on different types of data, where mSne and multi-SNE are two different methods to visualize multi-view data. We extended the  work in the paper [Multi-View Data Visualization Via Manifold Learning](https://arxiv.org/abs/2101.06763) from T. Rodosthenous, V. Shahrezaei, and M. Evangelou [2] by adding multi-isomap and multi-UMAP to reduce data dimensionality.

Please see sample code for more detail.

Work with [Yuan Hui](yhui@uchicago.edu).



# Data Description
[Handwritten Digits](https://archive.ics.uci.edu/ml/datasets/Multiple+Features): Consists of features on handwritten numerals (0 - 9) extracted from a collection of Dutch utility maps. 200 patterns per class (for a total of 2000 patterns) have been digitised in binary images. These digits
are represented in terms of six data-views: (a) Fourier coefficients of the character shapes (76 features), (b) profile
correlations (216), (c) Karhunen-Love coefficients (64), (d) pixel averages in 2 x 3 windows (240), (e) Zernike
moments (47 ) and (f) morphological features (6) Dua and Graff [2017].

[Caltech7](https://github.com/yeqinglee/mvdata): Caltech-101 contains pictures of objects belonging to 101 categories. This subset of Caltech-101 contains
only 7 classes and it was created because of the imbalanced number of objects in each class of Caltech-101. It consists
of 1474 objects on six data-views: (a) Gabor (48 features), (b) wavelet moments (40), (c) CENTRIST (254), (d)
histogram of oriented gradients (1984), (e) GIST (512), and (f) local binary patterns (928 ) Fei-Fei et al. [2006] .

[Cancer Types](http://compbio.cs.toronto.edu/SNF/SNF/Software.html): Consists of 65 patients with breast cancer, 82 with kidney cancer and 106 with lung cancer. This data set consists of three data-views: (a) genomics (10299 genes), (b) epigenomics (22503 methylation sites) and (c)
transcriptomics (302 mi-RNA sequences). The aim is to cluster patients by their cancer type Wang et al. [2014] .

Noisy Data-view Scenario (NDS): A simulated data set, which consists of 4 data-views and 3 true underlying clusters.
The first three data-views follow the same structure as in the toy example, while the 4th data-view represents a
completely noisy data-view, i.e. all data points lie in a single cluster. pv = 100; 8v, n = 300, equally balanced data
samples.

# Visualization and Accuracy

![image](https://user-images.githubusercontent.com/95513386/145927961-a8278201-8c83-4ff0-b228-d250f0e3b3c8.png)

![image](https://user-images.githubusercontent.com/95513386/145927976-c56dd96c-4767-4cb5-858f-5e10db5d315c.png)

![image](https://user-images.githubusercontent.com/95513386/145927987-077f7cac-9c4a-4800-8d24-49d24f655ba8.png)

![image](https://user-images.githubusercontent.com/95513386/145928001-e81d78c3-a880-48d3-b044-acbd3226489a.png)

![image](https://user-images.githubusercontent.com/95513386/145928017-21e57f94-677c-4876-bbb6-8964f41251fc.png)

![image](https://user-images.githubusercontent.com/95513386/145928327-144b0bbd-6cd6-4f57-ba85-9c6572a20464.png)


# Reference
[1] Bo Xie, Yang Mu, Dacheng Tao, and Kaiqi Huang. m-sne: multiview
stochastic neighbor embedding. IEEE Transactions on Systems,
Man, and Cybernetics, Part B: Cybernetics,. 41:1088???1096,
2011.

[2] Theodoulos Rodosthenous, Vahid Shahrezaei, and Marina Evangelou.
Multi-View Data Visualization Via Manifold Learning.
arXiv:2101.06763 , 2021.

[3] Laurens van der Maaten and Geoffrey Hinton. Visualising data using
t-sne. Journal of Machine Learning Research, 9:2579???2605,
2008.

[4] Leland McInnes, John Healy, James Melville. UMAP: Uniform
Manifold Approximation and Projection for Dimension Reduction
arXiv:1802.03426. 2018.

[5] George C. Linderman and Stefan Steinerberger. Clustering with
t-sne, provably. SIAM Journal on Mathematics of Data Science,
1(2):313???332, 2019.

[6] Solomon Kullback and Richard A. Leibler. On information and sufficiency.
22:79???86, 1951.

[7] https://archive.ics.uci.edu/ml/datasets/Multiple+Features

[8] http://compbio.cs.toronto.edu/SNF/SNF/Software.html

[9] https://github.com/yeqinglee/mvdata
