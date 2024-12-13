# Thesis Supplementary Materials
Supplementary Materials for my MSc Thesis, including code, ML predictions, and the pathway analysis

**Annotated Predictions**  
The ML model predictions with the original annotations for the to compounds to help us decide which ones to select for experimental validation. Note, as the annotations were originall made for internal communications only, they are not polished and may contain typos and internal memos

**Pathway Analysis of Training Hits**  
Contains the tallied differentially expressed pathways determined by IPA. Contains additional categories other than the Upregulated, Downregulated, Both, mentioned in the thesis. The Excel file contains comments that explain the additional categories

**Code and Data**  
Contains the Jupyter Notebook files for deployed model (one file for the frist set of predictions, another file for the second set of predictions from training on only the validated data)

The folder contains the pickle files for the fitted random forest models used. As a random seed was not specified during fitting, use the pickled models to obtain the same predictions.
