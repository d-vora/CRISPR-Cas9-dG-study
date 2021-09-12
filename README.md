# CRISPR-Cas9-energy-study
Machine learning approach to understand the importance of novel binding energy features in CRISPR/Cas9 activity prediction.

## Machine learning models
Classification models are employed to predict positive (experimentally-observed) off-target sequences from negative (similar but not acted upon by Cas9) off-targets.
Regression models are employed to predict the extent of Cas9 activity on the targets and positive off-targets.

The classification and regression ML models are written in Jupyter Notebook, the best performing model as well as other models tested are included. 
Feature importance analysis and results are also included. Initial data cleaning, sequence feature extraction and analysis steps are also included for reference.

## Novel features
Commonly-used sequence features such as nucleotide and mismatch positions, types of mismatches, PAM sequences and mismatches are used as features.
The novel features implemented are the binding energies between (1) DNA and guide RNA, and (2) Recognition (REC3) domain of Cas9 and the DNA-RNA hybrid.

## Feature importance analysis
The game-theory based Shapley Explanations (SHAP) are employed for determining the feature importance in driving model output for both classification and regression models. This in turn reflects on the mechanism of Cas9 activity.


The input data can be obtained on request.

(Suggestions are welcome!)
