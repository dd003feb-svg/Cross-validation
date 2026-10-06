Paper

Title: Hybrid Quantum-Classical Glaucoma Detection Using ResNet18 with Two-Qubit Variational Quantum Circuit

Problem: Glaucoma is a silent eye disease and a leading cause of irreversible blindness, so early screening is important.

Approach:A pre-trained ResNet18 extracts 512 features from each fundus image. These are reduced to 128 classical features and then to 2 quantum features. The 2 features are encoded into a two-qubit variational quantum circuit using Y-axis rotations. The Pauli-Z expectation values are fused with the 128 classical features into a 130-dimensional hybrid vector for Normal vs. Glaucoma classification.

Dataset: 970 retinal fundus images (626 normal, 344 glaucomatous), evaluated with 5-fold cross-validation.

Scope: The study tests the feasibility of a compact hybrid representation. It does not claim a quantum advantage over classical deep learning.
Results

Evaluated with 5-fold cross-validation (mean ± standard deviation across folds):

Metric	Value
Accuracy	96.10 ± 1.80 %
Sensitivity	93.00 ± 5.80 %
Specificity	97.80 ± 3.70 %
F1-score	94.40 ± 2.50 %
ROC-AUC	99.50 ± 0.70 %

Sensitivity varies the most across folds, which is expected because glaucoma is the smaller class (344 of 970 images).
