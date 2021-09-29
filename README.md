# Feature Selection

Feature Selection is the method of removing unwanted, irrelevant, less-informative and similar features from a dataset. This techniques aims to decrease the number of features used for modelling a data for classification or regression problems. It is also known by the name of Variable Selection, Attribute Selection, Variable Subset Selection or Feature Extraction. The reduction in the number of features helps in reducing computational cost and on the same time increasing the accuracy of a model and minimizing the chances of a model to go Overfit. 

Feature Selection is done with the help of multiple techniques, each of them are divided under 4 following categories:
1. Filter Methods
2. Wrapper Methods
3. Embedded Methods
4. Hybrid Methods

---

**Filter Methods** - Filter Methods perform Univariate Analysis and focus on one feature at a time. They handle high-dimensional data at a lower computational cost than the latter ones. The techniques which come under this category are:

- [Chi-Square Test](./chi_sq.ipynb)
- [Fisher's Score Test](./fisher_score.ipynb)
- [Correlation](./pearson_r.ipynb)
- [Variance Threshold](./variance_threshold.ipynb)
- [Mean Absolute Differance](./mean_abs_diff.ipynb)
- [Dispersion Ratio](./disp_ratio.py)
- [Mutual Dependence](./info_gain.ipynb)