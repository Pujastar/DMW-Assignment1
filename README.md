# DMW-Assignment1
6th semester DMW Assignment- generalization ability of SVM based on markov sampling

# Abstart:
We introduce a new Markov sampling algorithm for SVMC
to generate u.e.M.c. samples from given dataset, and present the
numerical studies on the learning performance of SVMC based
on Markov sampling for benchmark datasets.

# Algorithm
![image](https://user-images.githubusercontent.com/47221030/111444692-a74db600-8730-11eb-89df-4bf969cfb863.png)


# dataset
magic dataset
description of column
 1   fLength     19020 non-null  float64
 2   fWidth      19020 non-null  float64
 3   fSize       19020 non-null  float64
 4   fConc       19020 non-null  float64
 5   fConc1      19020 non-null  float64
 6   fAsym       19020 non-null  float64
 7   fM3Long     19020 non-null  float64
 8   fM3Trans    19020 non-null  float64
 9   fAlpha      19020 non-null  float64
 10  fDist       19020 non-null  float64
 11  class       19020 non-null  object
 
# result
![image](https://user-images.githubusercontent.com/47221030/111444228-2a224100-8730-11eb-8dc3-2cd53b0165ea.png)


mean misclassification rate for random sample with std (21.297318611987382, 0.2561270889440842)

![image](https://user-images.githubusercontent.com/47221030/111444299-3a3a2080-8730-11eb-8141-fe30ac975930.png)


mean misclassification rate for markov sample (21.04968454258675, 0.24574694356243504)
