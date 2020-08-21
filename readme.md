# Jupyter Notebook template for local development

## prerequisite

[poetry](https://python-poetry.org/docs/#installation) 

## environment

to make a virtual environment inside this project 

```
poetry config virtualenvs.in-project true
```

## setup this project

```
poetry install
```

## start

```
source .venv/bin/activate

jupyter contrib nbextension install --user
jupyter nbextensions_configurator enable --user

jupyter notebook
```

