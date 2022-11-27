data-science-template
==============================
## PROYECTO DE DETECCIÓN Y PREVENCIÓN DE FRAUDE

### Descripción de Proyecto

La detección de fraude en transacciones financieras ayuda a las empresas a identificar transacciones de alto riego. Es por ello, que cobra vital importancia realizar un análisis basado en algoritmos para evaluar el riesgo potencial de cada transacción.
El objetivo del proyecto es predecir fraudes en transacciones financieras. Para alcanzar este objetivo, el trabajo se estructura de la siguiente forma: 

<ol>
<li> Búsqueda de data set: para iniciar nuestro trabajo, realizamos una búsqueda del data set en Keagle. Para poder descargar el data set, hacer clic en el siguiente link:

<li> Análisis del Dataset: se realizará un análisis preliminar de la data, para identificar cantidad de registros y variables. Respecto a estas últimas se realizará un análisis de  Data Wrangling y análisis exploratorio (EDA) de la misma (análisis univariado, bivariado y multivariado).  

<li> Machine learning (ML): se entrenarán distintos modelos de clasificación, tomando como referencia el modelo Logistic Regression:

<ul>
<li>MODELO LINEAL</li> 
        <li>Logistic Regression</li>
        Ridge Classifier

 <li> MODELO TREE </li>
      Decision Tree Classifier </li>

  MODELO ENSEMBLE</li>
  Random Forest Classifier</li>
  XGBoost Classifier </li>
  Cat Boost Classifier </li>
  LightBoost Classifier

  MODELO NEIGHBORS  
  KNeighbors Classifier
  Nearest Centroid
Para la ejecución de cada modelo ulizaremos StratifiedKFold para finalizar con la Optimización Bayesiana. Por último para analizar la perfomance de cada modelo se aplicará la metrica Recall.
4.	Finalmente, en base a los resultado seleccionaremos los mejores modelos para construir un modelo ensamblado, utilizando stacking.


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
