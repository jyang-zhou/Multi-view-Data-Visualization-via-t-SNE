# Multi-view Data Visualization via t-SNE

mSNE and multi-SNE are implemented on different types of data, where mSne and multi-SNE are two different methods to visualize multi-view data. 

Please see sample code for more detail.

Work with [Yuan Hui](yhui@uchicago.edu)

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



