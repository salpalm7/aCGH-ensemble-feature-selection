# aCGH-ensemble-feature-selection
Ensemble feature selection for array CGH data

Cancer subtype identification is an important task in personalizing treatment plans for cancer, making accurate machine learning models desirable to help classify cancer subtypes. Array comparative genomic hybridization (aCGH) is a common technique for the identification of gene copy number gains and losses, which are associated with certain cancer (sub)types. Because these datasets show high dimensionality and limited sample sizes, feature selection is an essential task in order to prevent overfitting. Ensemble feature selection was evaluated using recursive feature elimination and iterative feature selection in combination with logistic regression, support vector machines and random forest models to build robust classifiers for predicting cancer subtype from aCGH data.

Results: Ensemble feature selection improves and stabilizes performance compared to individual feature selection techniques. Ensemble feature selection was able to identify biologically relevant biomarkers such as the ERBB2 gene, aiding classification of breast cancer subtypes.
