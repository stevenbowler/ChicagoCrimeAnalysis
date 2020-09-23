ChicagoCrimeAnalysis
==============================

Recent Trends in Chicago Crime 

Analysis of Chicago Crime data to determine if there are any recent changes in location, type or quantity of crimes reported.  The source of the data is the [Chicago Police Department Crime Database]() where the data contained represents crimes reported versus crimes charged.

The project is developed by [Steven Bowler](https://www.linkedin.com/in/stevenbowler1).

See  preliminary project definition [here](https://docs.google.com/document/d/1aKKIVhnydvb2Wx4-KtHw5w3NjtbGHZVZE2HP6YGI9KI/edit).

See original project proposal [here].

Original dataset accessed from [Chicago Crime Database](https://data.cityofchicago.org/Public-Safety/Crimes-Last-30-days/fjjk-7e4n)

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



### Setup Documetation
--------


Initial project file structure built with [CookieCutter Data Science Project Template](https://drivendata.github.io/cookiecutter-data-science/)
````
cookiecutter https://github.com/drivendata/cookiecutter-data-science
````