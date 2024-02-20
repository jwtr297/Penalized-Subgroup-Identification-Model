# Penalized Subgroup Identification Model

## Description
In various domains, many datasets exhibit both high variable dependency and group structures, which necessitates their simultaneous estimation. In this R package, we provide functions related to two subgroup identification methods based on penalized functions. These two methods, utilizing factor model structures, are adaptable to data with cross-sectional dependency. The first is the Center Augmented Factor Adjusted Regression Model (CAFARM) we proposed. Utilizing center-augmented penalty functions and factor structures, CAFARM eliminates data dependencies while identifying subgroups within datasets. We provide CAFARM methods optimized using Coordinate Descent and the Difference of Convex Alternating Direction Method of Multipliers (DC-ADMM), applicable for both L1 and L2 distance cases. The other model is the Factor-Adjusted Pairwise Fusion Penalty (FA-PFP) approach, which integrates factor augmentation into the pairwise fusion penalty framework by Ma and Huang (2017). We also provide a function for the Standard CAR (SCAR) method in this package, which does not consider the dependency and is for comparative analysis with our approaches. Furthermore, functions based on the Bayesian Information Criterion (BIC) are also included for selecting tuning parameters in CAFARM and FA-PFP.

## How to Use
To use the PSIM package, please first download the PSIM_0.1.0.tar.gz file and import it into your local R program. For detailed instructions on using the functions within the R package, please refer to the PDF file.
