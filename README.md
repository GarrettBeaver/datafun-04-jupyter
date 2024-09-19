# datafun-04-jupyter

## Create and Activate Project Virtual Environment

```shell
py -m venv .venv
.venv\Scripts\Activate
py -m pip install -r "requirements.txt"
```

## Freeze Requirements

```shell
py -m pip freeze > requirements.txt
```

## Git Add / Commit / Push 

```shell
git add .
git commit -m "add .gitignore, commands to README.md"
git push -u origin main
``

## How to install system requrements

```shell
py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy
```