# Replication package

## Requirements

- Python 3 (tested with Python 3.10)

## Structure

- calc_linguisitic_features.ipynb contains the code for the linguistic analysis
- statistical_analysis.ipynb contains the code for the analysis of the ratings and the overall statistical analysis
- the folder data contains the raw and processed data
- the folder markers contains helper files for the linguistic analysis
- the folder plots contains the plots we generated for this paper

## Usage example for Ubuntu 22.04

Execute the following commands in your terminal to setup the environment.

```
git clone https://github.com/sherbold/chatgpt-student-essay-study.git
cd chatgpt-student-essay-study
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

You can then start Jupyter Lab and open it in a browser to view and execute all code.

```
jupyter-lab
```