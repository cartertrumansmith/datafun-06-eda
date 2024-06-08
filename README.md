# datafun-06-eda
Project Repository for Module 6

### Initial Setup Commands
- Setup Virtual Environment:
```shell
python3 -m venv .venv
source .venv/bin/activate
```
- Install Requirements, Freeze to Requirements.txt:
```shell
pip install -r requirements.txt
python3 -m pip freeze > requirements.txt
```

### Dataset
I chose to use the [Tips](tips.csv) dataset from the Seaborn Library, I chose this dataset because it had Numerical columns (Tip, Total Bill and Size) as well as catergorical columns (Sex, Smoker, Day, Time). I want to analyze the relationship between these categories and how they correlate to tips and total bill.
