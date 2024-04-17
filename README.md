# ApproximateCFE

The Colab Notebooks provided implement the Approximate CFE algorithm across 10 datasets. These include:

CFE_datasets: Contains the original datasets used to train the Linear SVM.
ImplementationResults: Includes results for each dataset at different stages of the algorithm:
    Step 1 & 2: Identifies records that do not yield a Counterfactual Explanation (CFE) under strict constraints. These constraints are then relaxed. The results of these two steps are located in the folders marked as {dataset name}_L1.
    Step 3: Updates the hard constraint intervals using the slack values determined in Step 2, noted in the {dataset name}_L0.

Setup Instructions
To ensure the notebooks function correctly, follow these steps:

1. Upload Files: Transfer both the dataset and notebook files to your Google Drive.
2. Connect to Drive:
    Navigate to the "Connect to Drive" section of the notebook.
    Modify the path to reflect the location of your files on Google Drive.
3. Update File Paths:
    Check and update the file paths throughout the notebook to correspond with their locations in your Drive.


***Copyright 2024 by the authors' university which is unnamed because of KDD's anonymity requirement.***
