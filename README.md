# STELLAR CLASSIFICATION ANALYSIS 🔭

![Image 1](https://github.com/Siddhartha19Sinha/STELLAR-CLASSIFICATION-ANALYSIS/blob/main/Images/Image1.jpg)
![Image 2](https://github.com/Siddhartha19Sinha/STELLAR-CLASSIFICATION-ANALYSIS/blob/main/Images/Image2.jpg)
![Image 3](https://github.com/Siddhartha19Sinha/STELLAR-CLASSIFICATION-ANALYSIS/blob/main/Images/Image3.jpg)
![Image 4](https://github.com/Siddhartha19Sinha/STELLAR-CLASSIFICATION-ANALYSIS/blob/main/Images/Image4.jpg)

---

Welcome to the Stellar Classification Analysis project! This repository contains an in-depth analysis of stellar data, focusing on classifying stars, galaxies, and quasars based on their spectral characteristics.

## Overview ℹ️

In this project, we explore a dataset comprising 100,000 observations of space taken by the Sloan Digital Sky Survey (SDSS). Each observation is described by 17 feature columns and 1 class column, identifying it as a star, galaxy, or quasar.

## Dataset Details 📄

- *Source:* [Kaggle - Stellar Classification Dataset](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17)
- *Description:* The dataset includes information about various stellar attributes such as spectral type, magnitude, color index, luminosity, and more, collected from astronomical observations and surveys.

## Project Structure 📁

The repository is organized as follows:

- *Data:* Contains the stellar datasets used for analysis.
- *Notebooks:* Jupyter Notebooks (.ipynb) files containing the EDA and modeling process.
- *Visualizations:* Visualizations generated during the analysis.
- *Images:* Images used in the README.
- *README.md:* You are here!

## Data Exploration 🚀

- *Data Cleaning:* Handled missing values and duplicates.
- *Understanding Data Distribution:* Explored various stellar metrics such as right ascension angle, declination angle, and redshift values.
- *Exploratory Visualization:* Visualized data distribution using histograms, box plots, violin plots, and pair plots.
- *Feature Engineering:* Calculated color indices, extracted temporal features, performed one-hot encoding, and binned redshift values.

## Statistical Analysis 📊

- *t-Test:* Compared redshift values between galaxies and stars.
- *ANOVA:* Analyzed the redshift values across different classes.
- *Chi-Square Test:* Tested the independence between class and redshift category.

## Modeling 🧠

- *Linear Regression:* Predicted redshift values based on photometric filters (u, g, r, z).
- *Logistic Regression:* Classified stellar objects into stars, galaxies, or quasars.
- *Principal Component Analysis (PCA):* Reduced dimensionality for visualization.

## Advanced Visualization 📊

- *Interactive Visualization with Plotly:* Created interactive scatter plots.
- *Hierarchical Visualization with Dendrogram:* Plotted hierarchical clustering dendrogram.
- *Confusion Matrix:* Evaluated classification performance using a confusion matrix.

## Usage 📝

To replicate or explore the analysis:

1. Clone this repository:
  https://github.com/Siddhartha19Sinha/STELLAR-CLASSIFICATION-ANALYSIS

2. Navigate to the cloned directory:
  cd Stellar_Classification_Analysis

3. Install the required libraries:
  pip install -r requirements.txt

4. Open the Jupyter Notebooks in the Notebooks directory to view the analysis:
  jupyter notebook Notebooks/Stellar_Classification_Analysis.ipynb

## Contributors ✨
[Debolina Chatterjee](https://github.com/Debolina10Chatterjee)
[Siddhartha Sinha](https://github.com/Siddhartha19Sinha)
