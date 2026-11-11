
# Amazon Prime Video – EDA & Machine Learning

## Project Overview
This project analyses the Amazon Prime Video catalogue to explore its content distribution and identify factors associated with highly rated titles on IMDb.

It also develops a supervised machine learning classification model to predict whether a title is highly rated based on its available features.

## Project Details
- **Project Type:** Supervised Learning – Classification
- **Contribution:** Individual
- **Author:** Rachana F Patil

## Project Objectives
- Explore the Amazon Prime Video titles and credits datasets.
- Understand content distribution and rating patterns.
- Perform data cleaning and preprocessing.
- Analyse relationships between content characteristics and IMDb ratings.
- Develop machine learning models to classify highly rated titles.
- Evaluate model performance.

## Dataset Description
The project uses two datasets:

1. **Titles Dataset:** Contains information about movies and TV shows, including release year, runtime, seasons, age certification, genres, production countries and IMDb ratings.
2. **Credits Dataset:** Contains cast and director information associated with titles.

The datasets are merged to create a consolidated dataset for analysis and modelling.

## Methodology

### 1. Data Preparation
- Data cleaning and merging
- Duplicate handling
- Missing value treatment
- Feature extraction

### 2. Exploratory Data Analysis
- Univariate and bivariate analysis
- Distribution analysis
- Correlation analysis
- Hypothesis testing
- Visualisation of important patterns

### 3. Machine Learning
- Target variable creation using an IMDb rating threshold of 7.0
- Feature engineering and selection
- Categorical encoding
- Outlier treatment and numerical transformation
- Feature scaling
- Stratified train-test splitting
- Classification model training and evaluation

## Target Variable
Titles are classified into two categories:

- **High-rated:** IMDb score >= 7.0
- **Not high-rated:** IMDb score < 7.0

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook

## Repository Structure
- `notebooks/` – Data preparation, EDA and ML notebooks
- `data/` – Project datasets
- `models/` – Saved machine learning model
- `docs/` – Project reference material

## How to Run
1. Clone the repository.
2. Install the required dependencies:

   `pip install -r requirements.txt`

3. Open the notebooks using Jupyter Notebook or VS Code.
4. Run the notebooks in the required sequence.

## Results
The EDA findings, model evaluation metrics and conclusions are documented in the respective notebooks.

## Author
Rachana F Patil
