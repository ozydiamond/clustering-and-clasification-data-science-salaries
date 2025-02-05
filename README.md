# Clustering and Classification Data Science Salaries

## Description
This project using dataset: Data science salaries from kaggle

This project contains two main components:
1. **Clustering Analysis**: A project focused on grouping data into clusters to uncover hidden patterns.
2. **Classification Task**: A project for building a machine learning model to classify data into predefined categories.

These projects were completed as part of the final submissions for the "Belajar Machine Learning untuk Pemula" course in the Dicoding x IDCamp program path Data Science.

## Folder Structure
```
project/
├── data/               # Dataset files
├── notebook/           # Jupyter Notebook files
│   ├── clustering/     # Clustering project notebook
│   └── classification/ # Classification project notebook
├── requirements.txt    # List of dependencies
└── README.md           # Project documentation
```

## Prerequisites
To run this project, ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook or Jupyter Lab
- Required libraries (see `requirements.txt`):
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Clustering Project
1. Navigate to the `notebook/` folder.
2. Open the notebook file using Jupyter Notebook:
   ```bash
   jupyter notebook [Clustering]_Submission_Akhir_BMLP_Ahmad_Fuad.ipynb
   ```
3. Follow the instructions in the notebook to execute the clustering analysis.

### Classification Project
1. Navigate to the `notebook/` folder.
2. Open the notebook file using Jupyter Notebook:
   ```bash
   jupyter notebook [Klasifikasi]_Submission_Akhir_BMLP_Ahmad_Fuad.ipynb
   ```
3. Follow the instructions in the notebook to execute the classification task.

## Results
### Clustering
- Utilized algorithms: K-Means with 3 cluster
- Silhouette score: 0.7424
- Key insights:
   - Cluster 0: Senior employees (2022.46), high salary ($156K), 46.6% remote, large companies, full-time, in developed countries.
   - Cluster 1: Mid-level (2021.89), moderate salary ($73K), 59.6% remote, medium companies, full-time, in smaller firms.
   - Cluster 2: Entry-level (2021.57), low salary ($62K), 79.7% remote, small companies, part-time/contract, in startups/developing countries.

### Classification
- Utilized algorithms: Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbor.
- Model Accuracy: 99% (Decisision Tree)

## Acknowledgments
- Dicoding x IDCamp: "Belajar Machine Learning untuk Pemula" course materials.
- Mentors and peers who provided feedback and guidance.
