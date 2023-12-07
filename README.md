# Exploring the Applicability of Decision Trees to Automated Threat Modeling
Exploring the basics of decision trees and their applicability to automate threat modeling in the development and deployment of REST APIs.

# Reproducing the Experiments
The experiments are available in the included code notebook title `exploratory-decisions-trees.ipynb`.

The experiments require that the packages listed in `requirements.txt` be installed prior to executing any code from within the notebook.

It is recommended that you isolate these experiments and their requirements by installing the dependent Python packages within a virtual environment.

The experiments and the required Python package dependencies were originally tested using `pyenv`.

Reproducability requires a basic understanding of Python, Python package management, use of Jupyter Labs and/or Jupyter Notebooks, as well as an understanding of how to set up and manage virtual environments on a workstation.

## Virtual Environments
A virtual environment was originally created using Python v3.11.5, `pyenv`, and `virtualenv` on macOS.

### Creating a virtual environment
A virtual environment can be created on your workstation with the following command, given that the `pyenv` and `pyenv-virtualenv` software has been previously installed on your workstation.

```
pyenv virtualenv 3.11.5 decision-tree
```

### Using the virtual environment
The virtual environment named `decision-tree`, created in the previous section must be activated before it can be used to install Python dependencies. To activate the virtual environment execute the following command.

```
pyenv activate decision-tree
```

### Installing depdencies within the virtual environment
The virtual environment named `decision-tree`, created and activated in the previous two sections is now able to act as an isolated virtual environment for use with these experiments. The Python package dependencies can be installed within this virtual environment, assuming you've already executed the previous two steps.

```
pip install -r requirements.txt
```

# References
1. Wikipedia contributors. (2023, November 27). Decision tree learning. Wikipedia. https://en.wikipedia.org/wiki/Decision_tree_learning
2. Yang, S., PhD. (2021, December 15). Deep learning basics — input normalization - Analytics Vidhya - Medium. Medium. https://medium.com/analytics-vidhya/deep-learning-basics-input-normalization-670735d3a832
3. Almog, U. (2022, June 2). Decision Trees, explained - towards data science. Medium. https://towardsdatascience.com/decision-trees-explained-d7678c43a59e
