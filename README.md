[![Shipping files](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml/badge.svg?branch=main&event=workflow_dispatch)](https://github.com/neuefische/ds-eda-project-template/actions/workflows/workflow-03.yml)
# EDA project Marcus & Aps imaginary client: Charles Christensen

EDA project within the Neue Fische Bootcamp to learn and pratice EDA techniques and explore data in different ways.

in this repo, you will find:
- [data from sql database](./Fetching_the_data.ipynb) to upload and save your data from sql
- [slideshow](./realty_data_project-marcus_aps.pdf) about our presentation of results
- [documention](./Documentation.ipynb) with initial data checking an cleaning
- [code](./EDA_project.ipynd) wich the code concerning the data analysis
- info about [column names](./column_names.md) and the included values
- info about the [inital tasks](./assignment.md) and [workflow](./workflow.md)

## Requirements

- pyenv
- python==3.11.3


## Set up your Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need.

Before you can start with plotly in Jupyter Lab you have to install node.js (if you haven't done it before).
- Check **Node version**  by run the following commands:
    ```sh
    node -v
    ```
    If you haven't installed it yet, begin at `step_1`. Otherwise, proceed to `step_2`.


### **`macOS`** type the following commands : 


- `Step_1:` Update Homebrew and install Node by following commands:
    ```sh
    brew update
    brew install node
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :


- `Step_1:` Update Chocolatey and install Node by following commands:
    ```sh
    choco upgrade chocolatey
    choco install nodejs
    ```

- `Step_2:` Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    python -m pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    python -m pip install --upgrade pip
    pip install -r requirements.txt

## Data
The dataset for the notebook is stored as a csv in the data folder.
    ```
 
