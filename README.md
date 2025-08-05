# Smarter Marketing: Predicting Customer Decisions in Retail Banking

### ADS504 - Machine Learning and Deep Learning for Data Science

### Team 1

# Installation

To get started with this project, please clone the repository and navigate
to it:

```{bash}
> git clone https://github.com/junclemente/ads504-final_project.git
> cd ads504-final_project
```

## Environment Setup

This project uses a conda environment specified in a YAML file for
reproducibility and consistent development. Ensure you have
[Anaconda](https://www.anaconda.com/download) or
[Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main)
installed.

### Create the Environment

Run the following:

```{bash}
conda env create -f environment/ads504_project.yml
```

#### Update the Environment (if needed)

If there are any updates to the environment, you can update the environment
with the following:

```{bash}
conda env update -f environment/ads504_project.yml --prune
```

The `--prune` option cleans the environment by removing packages that are
no longer required.

# Contributors

- [Graham Ward](https://github.com/gw-00)
- [Michelle Wang](https://github.com/xuany823)
- [Jun Clemente](https://github.com/junclemente)

# Methods

- Exploratory Data Analysis
- Pre-processing
- Machine Learning
- Data visualization

# Technologies

- Python 3.10
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook / Google Colab
- VSCode

# Abstract

This study’s objective was to develop and evaluate multiple machine learning algorithms to accurately predict customer responses to marketing campaigns selling term deposits within the context of the popular Bank Marketing Dataset featured by The University of California Irvine’s Machine Learning Repository. Data is originally from the Portuguese Banking Institution’s Marketing Department phone call campaigns.

# Problem Statement

## Goal

Develop and evaluate machine learning models to accurately predict customer responses to marketing campaigns. The outcome will help optimize targeting strategies, reduce costs, and increase subscription rates for term deposit products.

# Google Colab

There are two Jupyter Notebooks included in this project. While we recommend running them in a local environment (where dependencies are already managed), you may also run them directly in Google Colab using the links below—no setup or installation required.

_Note:_ The Preprocess_Modeling.ipynb notebook may take up to 2 hours to complete due to the complexity of the model evaluation pipeline.

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) EDA.ipynb](https://colab.research.google.com/github/junclemente/ads504-final_project/blob/main/notebooks/EDA.ipynb)  

- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) Preprocess_modeling.ipynb](https://colab.research.google.com/github/junclemente/ads504-final_project/blob/main/notebooks/Preprocess_Modeling.ipynb)  

# Data Sources

UC Irvine ML Repository: Bank Marketing 
- [https://archive.ics.uci.edu/dataset/222/bank+marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- Observation: 41,188
- Features: 20

# Acknowledgements

# References

# Presentations and Projects

1.  Project Presentation: 
2.  Project Slides: [Canva](https://canva.com)
3.  Document Link: [Google Drive](https://drive.google.com)
4.  Project Repo: [https://github.com/junclemente/ads504-final_project](https://github.com/junclemente/ads504-final_project)
