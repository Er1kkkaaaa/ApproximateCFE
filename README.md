# ApproximateCFE

The Colab Notebooks implement the Approximate-CFE algorithm across the 10 datasets considered in the paper. Besides the algorithm implementation, the repository includes:

- The folder “CFE_datasets”, which contains the original datasets used to train the classifier;
- The folder “ ImplementationResults”, which includes results for each dataset at different stages of the algorithm, as described next.  Steps 1 & 2 refer to records that do not have a counterfactual explanation without relaxing soft requirements. These requirements are then relaxed. The results of first two steps are denoted as Step1_failed (containing the records for which no counterfactual explanation exists without relaxing soft requirements) and Step2 (containing the optimal values of the slack variables introduced to relax soft requirements). Step 3 refers to records for which a counterfactual explanation was found after relaxing soft requirements.


Setup Instructions: To ensure the notebooks function correctly, follow these steps:

1. Upload Files: Transfer both the dataset and notebook files to your Google Drive.
2. Connect to Drive: Navigate to the "Connect to Drive" section of the notebook. Modify the path to reflect the location of your files on Google Drive.
3. Update File Paths: Check and update the file paths throughout the notebook to correspond with their locations in your Drive


***Copyright 2024 by the authors' university which is unnamed because of KDD's anonymity requirement.***
