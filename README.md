<h1 align="center">Network Traffic Visualization</h1>

Visualization of log data from sample network traffic for Lab 3 of NTU's Net Centric Computing (CZ3006) course.

SFlow network data logs can be found in the `data` folder.

## Setup

The repository is set up in a Python virtual environment, including dependencies for common data science libraries such as pandas, matplotlib, networkx and seaborn.

Ensure that you have installed [Poetry](https://python-poetry.org/), a dependency manager for Python that creates virtual environments.

- `cd` to wherever you saved this repository folder to.
- Run `poetry install` to install project dependencies.
- Run `poetry run jupyter notebook` to start [Jupyter](https://jupyter.org/) in your local browser.
- Navigate to `notebooks` and open `network_traffic_visualization.ipynb`.
- Click `Cell > Run All`.
