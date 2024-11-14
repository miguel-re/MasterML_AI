# MasterML_AI
Repository that includes all codes of the master from University Tecmilenio.

# Overview

Since January 2024 I started my studies in University Tecmilenio, where I applied for a masters degree as specialist in Artifial Intelligence and Machine Learning MLOps.
I`ve used different tools such as:

- IBM Watson Studio
- Python:
  - LLM Models
  - Supervised and Unsupervised data and models
  - Neural Networks
  - Different libraries such as numpy, sklearn, pandas, seaborn, matplotlib.
- Jupyter notebooks.

# Structure of the project

Using data science cookie cutter strategy in each Module, task or evidence.

- README.md                     <-The top-level README using this project
- data                          
  - external                    <- Data from third party sources
  - interim                     <- Intermediate data that has been transformed
  - processed                   <- The final, canonical data set for modeling
  - raw                         <- The original, inmutable data dump.
- docs                          <- Docs in case of used
- models                        <- Trained models
- notebooks                     <- Jupyter notebooks
- references                    <- Data dictionaries, manuals
- reports                       <- Generated PDF, laTeX, etc.
  - figures                     <- Generated graphics and figures
- requirements.txt              <- The requirements file for reproducing the analysis environment
- {{cookiecutter.module_name}}  <- Source code for use this project
  - __init__.py                 <- Makes {{cookiecutter.module_name}} a Python module
  - config.py                   <- Store useful variables and config
  - dataset.py                  <- Scripts to download or generate data
  - features.py                 <- Code to create features for modeling
  - modeling                    
    - __init__.py               
    - predict.py                <- Code to run model inference with trained models
    - train.py                  <- Code to train models
  - plot.py                     <- Code to create plots
