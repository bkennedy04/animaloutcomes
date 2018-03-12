Animal Outcomes
==============================

Web app to predict shelter animal outcomes. You can download the original dataset [here](https://www.kaggle.com/c/shelter-animal-outcomes/data).

Project Organization
------------
	├── app	                       <- Files for developing flask app
	│   ├── static      
	│   └── templates
	└── develop          	       <- Files for developing predictive model
		├── LICENSE
		├── Makefile           <- Makefile with commands like `make data` or `make train`
		├── README.md          <- The top-level README for developers using this project.
		├── data
		│   ├── external       <- The original kaggle dataset.
		│   └── processed      <- The final, transformed canonical data sets for modeling
		│   
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
		├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
		│                         generated with `pip freeze > requirements.txt`
		│
		├── src                <- Source code for use in this project
		    ├── __init__.py    <- Makes src a Python module
		    │
		    ├── data           <- Scripts to download or generate data
		    │   └── make_dataset.py
		    │ 
		    ├── features       <- Scripts to turn raw data into features for modeling
		    │   └── build_features.py
		    │
		    └── models         <- Scripts to train models and then use trained models to make predictions
		        │                 
		        ├── predict_model.py
		        └── train_model.py     
		
		


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
