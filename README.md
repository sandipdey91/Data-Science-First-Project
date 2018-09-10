Jimmy Wrangler, Data Explorer
==============================

Data Acquisition and Exploration Project

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- NA
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- NA
    │   ├── interim        <- processed_movies_metadat.csv
    │   ├── processed      <- merged_data_set.csv, revenue_rating.csv.
    │   └── raw            <- IMDB_Rating.csv, movies_metadata.csv.        
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- NA
    │
    ├── notebooks          <- Dats Science First Project.ipynb.
    │
    ├── references         <- NA
    │
    ├── reports            <- report.pdf
    │   └── figures        <- plot.pdf
    │
    ├── requirements.txt   <- requirements.txt
    │
    ├── setup.py           <- jupyter notebook install
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
    └── tox.ini            <- tox file with settings for running tox; see tox.testrun.org


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
