# vclust

The **vclust** program implements a 3-step approach to facilitate the use of unsupervised clustering with the focus on user-defined validation. In step 1, it conducts unsupervised clustering based on multivariate outcomes using existing clustering methods such as growth mixture modeling (GMM), model-based clustering (MBC), and K-means clustering. In step 2, in each clustering, latent classes or clusters are regrouped into two coarsened clusters using all possible ways of splits, resulting in a large pool of binary labels. These labels are systematically validated using a priori sets of validators defined by the users. In step 3, the validated and selected labels are deployed in supervised learning.


## Installation

You can install **vclust** from github by using **devtools** library

```
install.packages("devtools")
devtools::install_github("zetan-li/vclust")
```
