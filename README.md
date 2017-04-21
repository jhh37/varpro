# Revisiting VarPro (CVPR 2017)

## Abstract
Variable Projection (VarPro) is a framework to solve optimization
problems efficiently by optimally eliminating a subset of the unknowns.
It is in particular adapted for Separable Nonlinear Least Squares (SNLS)
problems, a class of optimization problems including low-rank matrix
factorization with missing data and affine bundle adjustment as
instances. VarPro-based methods have received much attention over the
last decade due to the experimentally observed large convergence basin
for certain problem classes, where they have a clear advantage over
standard methods based on Joint optimization over all unknowns. Yet no
clear answers have been found in the literature as to why VarPro
outperforms others and why Joint optimization, which has been successful
in solving many computer vision tasks, fails on this type of problems.
Also, the fact that VarPro has been mainly tested on small to
medium-sized datasets has raised questions about its scalability. This
paper intends to address these unsolved puzzles. 

## Contributors
- Je Hyeong Hong (jhh37@outlook.com)
- Christopher Zach (christopher.m.zach@gmail.com)
- Andrew Fitzgibbon (awf@microsoft.com)

## Paper
The main paper and the supplementary document files are included in the
''Documents'' folder.

## Acknowledgment
- The work was supported by Microsoft and Toshiba Research Europe.
- We thank Roberto Cipolla for additional funding support.