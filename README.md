# Wafer Map Defect Pattern Classification (WM-811K)

Classifies semiconductor wafer map failure patterns (Center, Donut, Edge-Loc, Edge-Ring, Loc, Near-full, Random, Scratch, none) using interpretable, rotation- and scale-invariant features and a linear SVM. The methodology follows Wu, Jang & Chen (IEEE Trans. Semiconductor Manufacturing, 2015), reimplemented in Python on the public WM-811K dataset.

Each wafer map is reduced to 34 features (regional defect density, geometry of the most salient defect region, and Radon-transform profiles), scaled, and classified with a class-balanced LinearSVC. The project shows how physically meaningful features can separate defect types on a highly imbalanced, real-world fab dataset.


SVM-based wafer map defect classification on WM-811K using Density, Geometry and Radon features, following Wu, Jang & Chen (2015).
