soccer-analytics-d4
==============================

England vs Denmark Match Analysis Project

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── skillcorner      <- data offered from skillcorner
    │   └── wyscout          <- data offered from wyscout
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

# England vs Denmark Match Analysis Project

This repository is dedicated to a comprehensive analysis aimed at preparing the England national football team for an upcoming match against Denmark. By leveraging a variety of data sources and analytical techniques, this project seeks to provide insights into the performances, strategies, and key players of both teams. The ultimate goal is to furnish the England team with actionable intelligence to enhance their preparation and performance.

## Project Structure

The analysis is divided into several key sections, each focusing on different aspects of the game:

### Historical Data and Exploratory Analysis

**Objective**: To gather and analyze historical match results between England and Denmark, assess FIFA world rankings and their influencing factors, evaluate key players and their FIFA ratings, and examine ball possession statistics.

### Tracking Data

**Objective**: To analyze games from the qualifiers using Voronoi diagrams to identify tactical ideas, understand how each team plays, and confirm these observations with data. This includes identifying strengths and weaknesses and observing how teams change formation across different zones of the pitch.

### Team Formation and Movement

**Objective**: To analyze Denmark's team formations and movements in various matches using positional data, with a focus on a 4-3-3 formation variant and how the team occupies space on the pitch.

### Shot Analysis

**Objective**: To examine the shots taken by and against Denmark to identify patterns, weak spots, and strong attacking patterns. This includes analyzing shots from different game situations (e.g., free kicks, corners, headers) and calculating expected goal probability (xG).

### Passing Analysis

**Objective**: To conduct an in-depth analysis of passing patterns, accuracy, and effectiveness during the games to understand how teams build their attacks and maintain possession.

## Delegation

- Kari: Team formations and movement
- Roman: xG and shooting, goal scoring, set pieces, header
- Sonja: Past results/specific players
- Thomas: Passing/Pressing
- Ahash: What players have the most influence?

## Key Players for Each Team

### Denmark:

- **Rasmus Højlund** - Centre-Forward
- **Christian Eriksen** - Central Midfield
- **Andreas Christensen** - Centre-Back

### England:

- **Harry Kane** - Centre-Forward
- **Jude Bellingham** - Attacking Midfield
- **Kyle Walker** - Right-Back

## Past UEFA Stats

- England's average goals scored per match: 2.75
- England's average conceded goals per match: 0.5
- Denmark's average goals scored per match: 1.9
- Denmark's average conceded goals per match: 1

## Previous Encounters

- UEFA EURO 2020: England 2 - 1 Denmark
- Nations League: England 0 - 0 Denmark
- Nations League: England 0 - 1 Denmark

## FIFA Rankings

- England: 3rd Place, 1800.05 Points
- Denmark: 21st Place, 1601.31 Points

## Contribution

This project is a collaborative effort. Contributions are welcome, especially in areas such as passing/pressing analysis, player influence, and further exploration of shot statistics and team strategies.

## Conclusion

By combining detailed historical data, player analysis, and tactical insights, this project aims to provide the England national football team with a strategic advantage in their preparation for facing Denmark. Through careful analysis and teamwork, we strive to uncover valuable insights that can contribute to a successful performance.


<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
