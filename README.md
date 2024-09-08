# Impact of Molecular Descriptors on Solubility Prediction in Chemical Compounds 🧪📊

Welcome to the Solubility Prediction project! This project aims to understand the relationship between molecular descriptors and solubility in chemical compounds, crucial for medication design and environmental research.

## Table of Contents
- [Introduction](#introduction)
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)
- [Analysis](#analysis)
- [Model Building](#model-building)
- [Conclusion](#conclusion)
- [References](#references)

## Introduction
A compound's solubility affects its absorption, distribution, metabolism, and excretion, making it a crucial attribute in medication design and environmental research (Lipinski et al., 2001). The dataset contains various molecular descriptors, including topological polar surface area (TPSA), number of hydrogen bond acceptors and donors, molecular weight, LogP, and more.

Understanding the relationship between these characteristics and solubility can lead to more accurate predictive models and better medication formulations and environmental risk assessments. Previous studies have demonstrated that descriptors such as LogP and TPSA have a significant impact on solubility because of their functions in molecular surface properties and intermolecular interactions (Hou, Xu & Lee, 2009).

## Data Cleaning & Preprocessing
Data preprocessing and cleansing are crucial in data analysis and machine learning (Zhu et al., 2019). The dataset includes chemical compounds and their properties like solubility, molecular weight, and topological polar surface area (Kotsiantis, Kanellopoulos & Pintelas, 2006).

## Analysis
- **Descriptive Statistics & Univariate Analysis:** Provides insights into the dataset's central tendency, dispersion, and distributional shape.
- **Bivariate Analysis:** Investigates the connection between two variables.
- **Multivariate Analysis:** Examines multiple variables simultaneously to identify complex relationships and patterns.
- **Principal Component Analysis (PCA):** Reduces dimensionality by condensing large variables into manageable sets.
- **Cluster Analysis:** Groups items according to similarities, identifying patterns and data structures.

## Model Building
Three regression models are examined: Random Forests, Decision Trees, and Linear Regression. Random Forests surpass Linear Regression in explaining 62% of the variance in solubility.

## Conclusion
The dataset containing information on the solubility and molecular characteristics of several compounds was evaluated. The results showed significant variability in terms of solubility values, which were largely concentrated between -2 and 0. Additionally, the distribution of molecular weights was skewed to the right, and metrics like MolLogP and MolMR showed distinct patterns. Bivariate analysis revealed significant connections between solubility and molecular characteristics. The most accurate model for predicting solubility, according to the data, was Random Forest.

## References
- [Lipinski, C.A., et al., 2001](https://www.sciencedirect.com/science/article/abs/pii/S0169409X00001519)
- [Hou, T., Xu, X. & Lee, S., 2009](https://pubs.acs.org/doi/10.1021/ci800159k)
- [Zhu, X., et al., 2019](https://sites.google.com/site/ijcsis/)
- [Kotsiantis, S., et al., 2006](https://www.ijcse.com/docs/IJCSE06-01-02-14.pdf)


Thank you! 🌟
