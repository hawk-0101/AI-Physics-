# AI-Physics-Higgs Boson

Dataset source: Kaggle Higgs Boson dataset — https://www.kaggle.com/datasets/knight079/higgsb

Structure: training.csv (labels) and test.csv (no labels) with 33 columns (includes engineered features/IDs).

Rationale: The original CERN file is ~11GB (11M events); I can’t afford that locally, so I’m using Kaggle for feasibility.

Workflow: Load training.csv → preprocess/normalize → stratified train/val split → train LR/RF/XGB → evaluate → optional submission on test.csv..

Reproducibility: Fixed seeds, config-driven hyperparameters, and environment files provided.
