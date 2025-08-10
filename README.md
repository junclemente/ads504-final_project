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

This study’s objective was to develop and evaluate multiple machine learning algorithms to accurately predict customer responses to marketing campaigns selling term deposits within the context of the popular Bank Marketing Dataset featured by The University of California Irvine’s Machine Learning Repository. Data is originally from the Portuguese Banking Institution’s Marketing Department phone call campaigns. Our team utilized a structured, analytical approach to perform exploratory data analysis, pre-processing, feature engineering and the development of different classification models to include Perceptron, Logistic Regression, K-Nearest Neighbors, Support Vector Classifiers, XGBoost, AdaBoost, Random Forest and Neural Networks. In order to reduce overfitting all models were split into training and testing sets and five-fold cross-validation was performed on the training data and results were averaged and stored in full. The final model performance on the testing data evaluates to how well the models generalize to unseen data. While all models performed well, the clear winner was the XGBoost model which achieved the highest Accuracy, Precision and AUC-ROC score in both training and testing datasets. This model was selected as the best model to begin building a model for purposes of identifying customers for term deposit accounts in a bank marketing department setting.

# Objective

The objective of our analysis is to build predictive models that can accurately classify whether a customer is likely to subscribe to a term deposit based on their personal and interaction data. By applying machine learning techniques, we aim to identify patterns and variables that influence customer decisions, improve campaign targeting, and optimize marketing resources. This analysis helps the bank target likely subscribers, reduce marketing costs, and improve conversion rates. By predicting customer behavior, the bank can deliver more efficient, personalized campaigns and make better use of its resources.

# Google Colab

There are two Jupyter Notebooks included in this project. While we recommend running them in a local environment (where dependencies are already managed), you may also run them directly in Google Colab using the links below—no setup or installation required.

_Note:_ The Preprocess_Modeling.ipynb notebook may take up to 30 minutes or longer to complete due to the complexity of the model evaluation pipeline.

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
