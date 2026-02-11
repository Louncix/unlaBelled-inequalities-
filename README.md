# unlaBelled-inequalities-
Contains functions and data related to the "unlaBelled Bell scenarios", corresponding to Bell inequalities involving only equality comparisons between outcomes


This repository contains code and data associated with the article:

[Bell Inequalities for Smells], Authors, arXiv:XXXX.XXXXX (2026)

If you use this code or data, please cite the corresponding paper.


Data in this repository: 


**S_33 inequality**
Matlab variable containing the S_33 inequality given in the main text, in two formats: 'S_33_Smells' gives the coefficient in a vector, in the same order as given on the paper, while 'S_33_Full' gives the coefficient in a vector that corresponds to full-probability notation, with ordering "Bob changes first, outputs change first", that is: ab|xy => 00|00 01|00 02|00 10|00 11|00 12|00 20|00 21|00 22|00   00|01 01|01 02|01 10|01 11|01 12|01 20|01 21|01 22|01 etc. 

**Rho_rank2_and_measurements_paper.mat:**
Matlab variable containing the density matrix and corresponding measurements to violate the I_{33} inequality. The density matrix 'Rho' is a 4x4 psd trace-1 matrix, while 'A' is an array, corresponding to Alice's local POVMs, where A(:,:,a,x) is the element corresponding to outcome 'a' and 'input 'x', and 'B' is an array, corresponding to Bob's local POVMs, where B(:,:,b,y) is the element corresponding to outcome 'b' and 'input 'y'
