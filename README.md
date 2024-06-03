# datafun-06-eda
#### This Read Me file contains the information and instructions related to Project 6 EDA

[mpg.csv](https://github.com/mwaskom/seaborn-data/blob/master/mpg.csv)

## Instructions for cloning Repo to computer
```bash
git clone https://github.com/K-Bromley/datafun-06-eda
```

## Instructions for Setting up Virtual Environment
``` bash
python3 -m venv .venv
source .venv/bin/activate
```

## Installing dependencies and freezing requirements
```bash
python3 -m pip install jupyterlab pandas pyarrow matplotlib seaborn
python3 -m pip freeze > requirements.txt
```

## Data Set Load
```bash
df = sns.load_dataset('mpg')
```

## Git Commands
``` bash
git add .
git commit -m ""
git push origin main
```