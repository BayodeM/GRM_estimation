# GRM_estimation
Individual relationships estimated using genotypes
This is a python program that was created to estimate the genomic relationship using VanRaden method 1.
The genotype file should be accompanied by a corresponding map file
The program does the filtering from MAF, proportion missing genotypes, which is provided by the user.
By default a difference between the observed and expected heterozygous of 0.15 is used to filter for deviation from HWE.
In addition, users can specify to use obsereved frequency (0) or fixed frequency (1) in the estimation of the GRM
