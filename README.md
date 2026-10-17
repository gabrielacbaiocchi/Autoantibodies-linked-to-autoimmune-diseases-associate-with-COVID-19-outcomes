# Autoantibody signatures associated with COVID-19 severity

Analysis code for:

Baiocchi GC, Vojdani A, Rosenberg AZ, et al.
**Cross-sectional analysis reveals autoantibody signatures associated with COVID-19 severity.**
*Journal of Medical Virology* 2023;95(2):e28538. https://doi.org/10.1002/jmv.28538

## Study

IgG and IgA autoantibodies linked to autoimmune diseases were measured in 231 individuals:
161 COVID-19 patients (72 mild, 61 moderate, 28 severe) and 70 healthy controls, all sampled
before vaccination. Dysregulated autoantibody levels, mainly elevated concentrations, occurred
predominantly in moderate and severe disease, and autoantibody levels tracked with
anti-SARS-CoV-2 antibody concentration and age as classifiers of severity.

## Analyses in this repository

- Group comparisons of autoantibody levels (Kruskal-Wallis with Dunn post hoc, FDR-adjusted)
- Autoantibody correlation signatures and hierarchical clustering
- Multi-study factor analysis
- Principal component analysis with spectral decomposition
- Random-forest classification of severity (5,000 trees; variable importance by Gini decrease,
  mean minimum depth and node count; evaluated by out-of-bag error and ROC)

Code is in `R codes/`. Data are in the paper's Supporting Information.

## Citation

If you use this code, please cite the paper above.
