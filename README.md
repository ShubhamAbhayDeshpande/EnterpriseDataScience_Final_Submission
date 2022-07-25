ADS_covid-19
==============================

Applied Data Science on covid 19

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

## Python version and libraries used:
Python = 3.7.x

Libraries:

Numpy

Pandas

Matplotlib

scikitlearn

seaborn

dash(plotly)

facebook prophet

## Note: 
Folder named 'data' is purposefully kept empty (Because of the size restriction on github). To run all the notebooks successfully clone the following repository into the specified path after cloning this repository 

repository: https://github.com/CSSEGISandData/COVID-19.git

path: data >> raw

# Sneak peak into the notebook

### 1. Timeline for confirmed cases

![](https://github.com/ShubhamAbhayDeshpande/EnterpriseDataScience_Final_Submission/blob/main/timeline_confirmed.gif) 

### 2. Timeline for doubling rate
![](https://github.com/ShubhamAbhayDeshpande/EnterpriseDataScience_Final_Submission/blob/main/timeline_doubling_rate.gif)

### 3. Confirmed cases filtered
![](https://github.com/ShubhamAbhayDeshpande/EnterpriseDataScience_Final_Submission/blob/main/timeline_confirmed_filtered.gif)

### 4. Timeline for filtered doubling rate
![](https://github.com/ShubhamAbhayDeshpande/EnterpriseDataScience_Final_Submission/blob/main/doubling_rate_filtered.gif)

### 5. SIR modelling
![](https://github.com/ShubhamAbhayDeshpande/EnterpriseDataScience_Final_Submission/blob/main/SIM.gif)