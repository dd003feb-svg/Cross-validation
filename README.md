Paper

Title: Hybrid Quantum-Classical Glaucoma Detection Using ResNet18 with Two-Qubit Variational Quantum Circuit

Problem: Glaucoma is a silent eye disease and a leading cause of irreversible blindness, so early screening is important.

Approach:A pre-trained ResNet18 extracts 512 features from each fundus image. These are reduced to 128 classical features and then to 2 quantum features. The 2 features are encoded into a two-qubit variational quantum circuit using Y-axis rotations. The Pauli-Z expectation values are fused with the 128 classical features into a 130-dimensional hybrid vector for Normal vs. Glaucoma classification.

Dataset: 970 retinal fundus images (626 normal, 344 glaucomatous), evaluated with 5-fold cross-validation.

Scope: The study tests the feasibility of a compact hybrid representation. It does not claim a quantum advantage over classical deep learning.
