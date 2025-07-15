# Assignment4 Stats Scripts

A hands-on Python notebook covering foundational statistical analysis, hypothesis testing, and data visualization using real-world datasets.

This repository contains a Jupyter Notebook based on the ["Statistics in Python" tutorial](https://scipy-lectures.org/packages/statistics/index.html) by Gaël Varoquaux. The notebook includes data manipulation using pandas, statistical testing with `scipy.stats`, and modeling via `statsmodels`, using datasets such as `brain_size.csv`, `iris.csv`, and `wages.csv`.

## Table of Contents

* [Background](#background)
* [Install](#install)
* [Usage](#usage)
* [Examples](#examples)
* [License](#license)
* [Acknowledgments](#Acknowledgments)
  
## Background
This notebook contains an introduction to statistics using Python, aimed at students who want to:

* Explore statistical tests like t-tests, ANOVA, and regression.
* Use pandas and seaborn to manipulate and visualize data.
* Understand the use of linear models and interaction terms.

## Install

Clone this repository and set up the environment using `conda`:

```bash
git clone https://github.com/chong-lu/Assignment4-Stats-Scripts.git
cd Assignment4-Stats-Scripts
conda env create -f environment.yml
conda activate stats-env
```

## Usage

Launch the notebook using JupyterLab:

```bash
jupyter lab 
```

The notebook(notebooks/stats_python.ipynb) covers:

* Loading and cleaning datasets (`brain_size.csv`, `wages.csv`, `iris.csv`)
* Descriptive statistics and visualization
* One-sample, two-sample, and paired t-tests
* Linear regression and ANOVA
* Interaction effects using multiple regression
* Seaborn visualizations for exploratory analysis

## Examples

Some key analyses included:

* IQ analysis by gender using brain imaging data
* Regression analysis on the iris dataset
* Wage analysis with education, gender, and interaction effects

Example includes code, interpretation of results (e.g., p-values), and plots generated with seaborn or matplotlib.

## License

This repository is intended for educational use only.

## Acknowledgments

- Based on exercises from:

https://scipy-lectures.org/packages/statistics/index.html
- Readme template from:

https://github.com/RichardLitt/standard-readme