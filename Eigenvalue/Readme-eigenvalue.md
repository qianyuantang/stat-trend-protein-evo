# Folder "Eigenvalue"

* In every text file, each row corresponds to the calculated results of a given predicted protein structure. Each row of data corresponds to the predicted protein structure whose file name is listed in the corresponding text file in the "Index" folder.

* The folder "SlowMode" contains text files of the slowest nonzero eigenvalue of the predicted protein structure from all the 48 organisms in AlphaFold DB. In the calculation, the eigenvalues are normalized (see Method part of the Main Text).

* The folder "Gap" contains text files related to the log-eigengaps of the proteins from the 16 model organisms.

* In the text file, the data listed in each column are:
- Column 1, $\lambda_2 / \lambda_1$.
- Column 2, $\lambda_3 / \lambda_2$.
- Column 3, $\lambda_4 / \lambda_3$.
- Column 4, $\lambda_5 / \lambda_4$.

* Every filename contains information about the reference proteome, the number of proteins, and the species code.
