# Metrics-Analysis

## About

In this repository are some statistical analysis of various software metrics from the [NASA MDP](https://github.com/klainfo/NASADefectDataset/tree/master) dataset. The metrics are analyzed using the python programming language.

## Setting up Python Environment

1. Install [Python 3.7](https://www.python.org/downloads/release/python-370/)
2. Install [pip](https://pip.pypa.io/en/stable/installing/)
3. Go to the root directory of the project and run the following command:
   `python -m venv .`
4. Activate the virtual environment by running the following command:
   `.\Scripts\activate`
   (If you are using Bash, run the following command instead: `source Scripts/activate`)
5. Install the required packages by running the following command:
   `pip install -r requirements.txt`

## Side Note

- You may need to install the Jupyter Notebook Renderers extension for VS Code to render the graphs in the notebook. You can install it [here](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter-renderers). Then, change the presentation of your Notebook's output cell to `application/vnd.plotly.v1+json`.
