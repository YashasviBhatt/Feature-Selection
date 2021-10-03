# Feature Selection

Feature Selection is the method of removing unwanted, irrelevant, less-informative and similar features from a dataset. These techniques aims to decrease the number of features used for modelling a data for classification or regression problems. It is also known by the name of Variable Selection, Attribute Selection, Variable Subset Selection or Feature Extraction. The reduction in the number of features helps in reducing computational cost and on the same time increasing the accuracy of a model and minimizing the chances of a model to go Overfit. 

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

---

**Wrapper Methods** - Wrapper Methods uses the pre-configured estimators, these estimators have weights assigned to features. Now the wrapper methods uses these configured estimators to select the best features. They select the features one by one and make combinations of them. These combinations are then used to fit a model using the estimator provided. Lastly, the best set of features whose model performs best among all of them will be chosen as the final subset of features. The techniques which come under this category are:

- [Forward Feature Selection](./frwrd_ft_sel.ipynb)
- [Backward Feature Selection](./bckwrd_ft_sel.ipynb)
- [Bi-Directional Feature Selection](./)
- [Exhaustive Feature Selection](./ex_ft_sel.ipynb)
- [Recursive Feature Selection](./rcrsv_ft_sel.py)