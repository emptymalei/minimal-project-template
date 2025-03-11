# Overview

{{cookiecutter.project_short_description}}

## Setup

### Requirements

* Python {{cookiecutter.python_major_version}}.{{cookiecutter.python_minor_version}}+

### Development

1. Install pre-commit hooks: `pre-commit install`
2. Install dependencies `poetry install`


### Use Jupyter Notebooks

1. Put notebooks in the `notebooks` folder.
2. Run `poetry run jupytext --sync notebooks/*py*` to sync the git commitable script and the notebooks.
