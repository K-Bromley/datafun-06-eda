# datafun-06-eda
#### This Read Me file contains the information and instructions related to Project 6 EDA

## Link to Data File Location
[mpg.csv](https://github.com/mwaskom/seaborn-data/blob/master/mpg.csv)

## Instructions for cloning Repo to computer
```zsh
git clone https://github.com/K-Bromley/datafun-06-eda
```

## Instructions for Setting up Virtual Environment
``` zsh
python3 -m venv .venv
source .venv/bin/activate
```

## Installing dependencies and freezing requirements
```zsh
python3 -m pip install jupyterlab pandas pyarrow matplotlib seaborn
python3 -m pip freeze > requirements.txt
```

## Data Set Load
```python
df = sns.load_dataset('mpg')
```

## Plots Used
```python
df[].hist()
sns.countplot
sns.pairplot
sns.barplot
sns.scatterplot
```

## Git Commands
``` zsh
git add .
git commit -m ""
git push origin main
```