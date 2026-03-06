# FlimFlam: Automated Online Transaction Fraud Detection

FlimFlam is a machine learning-based system designed to automatically detect fraudulent online transactions. The system aims to build a robust fraud detection pipeline that supports automatic model retraining, monitoring, and scalable deployment following MLOps best practices.

#### Project Status
Active Development

## Project Objective
The project is developed as part of the **Machine Learning Operations (MLOps) – CIF60050** course. 

## Project Workflow

The fraud detection pipeline consists of the following stages:

1. Data Ingestion  
2. Data Preprocessing  
3. Feature Engineering  
4. Model Training  
5. Model Evaluation  
6. Model Deployment  
7. Monitoring & Model Update

The system implements an automated model update mechanism to handle concept drift in fraudulent transaction patterns.

### Methods Used
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Supervised Machine Learning
- Fraud Detection Modeling
- Inferential Statistics
- Model Evaluation Metrics
- MLOps Pipeline Automation
-[Updated as the development go]

### Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- GitHub Codespaces
- uv (Python package manager)
- [Updated as the development go]

## Project Structure
```
MLOps-FlimFlam
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see www.mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         {{ cookiecutter.module_name }} and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── dev  <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations   
```

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](https://www.kaggle.com/competitions/ieee-fraud-detection) within this repo.

    *The dataset are limited to kaggle competition. Make sure you are login with a Kaggle account and agree with the competition's term and conditions*

    *If using offline data mention that and how they may obtain the data from the froup)*
    
3. [Updated as the development go]

4. Follow setup [instructions](Link to file)

## Installation

1. **Clone the repository**

    ```bash
    git clone git@github.com:Pieter414/MLOps-FlimFlam.git
    cd MLOps-FlimFlam
    ```

2. **Prerequisites & Installing Dependencies**

    ```bash
    uv sync
    source venv/bin/activate  # Linux/Mac
    venv\Scripts\activate     # Windows
    ```

## Dataset

This project uses the **IEEE-CIS Fraud Detection Dataset** from Kaggle.

Dataset source:
https://www.kaggle.com/competitions/ieee-fraud-detection

The dataset contains anonymized transaction data and identity information used to detect fraudulent online transactions.

To download the dataset:

1. Create a Kaggle account
2. Accept the competition rules
3. Download the dataset
4. Place the files in:

data/raw/

## Running the Project with GitHub Codespaces

1. Open the repository in GitHub
2. Click **Code**
3. Select **Codespaces**
4. Click **Create Codespace on main**

Once the environment is ready, install dependencies:

```bash
uv sync
```

<!-- ## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link) -->


## Author

Pieter Christy Yan Yudhistira

Email: pieterchristyan7@gmail.com  
LinkedIn: https://www.linkedin.com/in/pieter-christy-yan-yudhistira/