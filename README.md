# Smart Contract Dataset Analysis

This project involves exploratory data analysis (EDA) on a dataset of smart contracts deployed on various blockchain networks. The goal is to understand the dataset, identify patterns and anomalies, and propose preprocessing and modeling approaches for future tasks.

## Project Structure

    .
    ├── README.md               # Instructions for setup and usage
    ├── data/                   # Directory for storing the dataset
    │   └── test_dataset.csv    # Dataset file (to be added manually)
    ├── eda.ipynb               # Jupyter Notebook for exploratory data analysis
    ├── poetry.lock             # Lock file for Poetry dependencies
    └── pyproject.toml          # Poetry configuration and dependency management

## Installation

To set up the project environment and install all dependencies, follow the steps below.
Then copy your data files to the data folder.
Run pipeline.

### Prerequisites

	-	Python 3.10+ installed on your system.
	-	Poetry package manager for Python.

### Install Poetry

If you don’t have Poetry installed, you can install it using the following command:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Alternatively, refer to the official Poetry installation guide for more options.

### Set Up the Project Environment

1.	Clone the Repository
Clone the project repository to your local machine:

```bash
git clone https://github.com/lezhocheck/contracts-explore.git
```

2.	Install Dependencies
Run the following command to install all project dependencies as specified in the pyproject.toml file:

```bash
poetry install
```

This command will create a virtual environment (if one doesn’t exist) and install all the required packages.

3.	Activate the Virtual Environment
To activate the virtual environment created by Poetry, run:

```bash
poetry shell
```


4. Add the Dataset

Copy your dataset file (test_dataset.csv) to the data directory.

Ensure the file name matches test_dataset.csv for seamless execution.

5. Run the EDA Notebook
    The notebook contains detailed exploratory data analysis with visualizations and insights (report).
	