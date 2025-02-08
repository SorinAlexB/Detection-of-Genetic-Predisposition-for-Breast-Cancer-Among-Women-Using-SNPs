# Detection of Genetic Predisposition for Breast Cancer Among Women Using SNPs

## Overview

This project aims to identify correlations between Single Nucleotide Polymorphisms (SNPs) in the genes of patients suffering from breast cancer. By analyzing genetic data, we can predict predisposition to this disease.

## Dataset

The dataset used in this project contains genetic information of women diagnosed with breast cancer and those without the disease. It includes SNP markers relevant to breast cancer susceptibility.

Dataset source: [Springer Nature](https://springernature.figshare.com/articles/dataset/Dataset_containing_genotype_data_for_single_nucleotide_polymorphism_markers_in_sporadic_breast_cancer_related_genes_in_a_Sri_Lankan_case-control_cohort_of_postmenopausal_women/7159514)

## Project Workflow

1. **Loading the Dataset**: The dataset consists of genes in the first row, SNPs in the second row, and the genetic variations in subsequent rows.
2. **Data Preprocessing**: Handling missing values, encoding SNPs, and normalizing data for analysis.
3. **Exploratory Data Analysis (EDA)**:
   - Distribution of SNPs
   - Correlations between SNPs and breast cancer status
   - Visualization of allele frequencies
4. **Feature Selection**: Identifying significant SNPs associated with breast cancer risk.
5. **Model Training & Evaluation**:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Random Forest
   - Neural Networks
   - Performance metrics: Accuracy, Precision, Recall, F1-score, AUC-ROC
6. **Prediction & Interpretation**: Using trained models to predict genetic predisposition and interpret significant SNPs.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

Install dependencies using:

```sh
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Clone the repository:

```sh
git clone https://github.com/yourusername/genetic-predisposition-breast-cancer.git
cd genetic-predisposition-breast-cancer
```

2. Run the Jupyter Notebook:

```sh
jupyter notebook Detection_of_genetic_predisposition_for_breast_cancer_among_women_using_SNPs.ipynb
```

3. Follow the steps in the notebook to analyze the dataset and train models.

## Results

The results include:

- Identified significant SNPs related to breast cancer
- Performance evaluation of different machine learning models
- Visualizations of SNP distributions and correlations

## Contributions

Feel free to contribute by submitting pull requests or raising issues for improvements.

## License

This project is open-source and licensed under the MIT License.
