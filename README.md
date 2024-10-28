# django custom css

## Prerequisites

### Python 3

`py` command should point to python3

```shell
py -V
# 3.10.0
```

### Check git is installed

```
git --version
```

## Create a new folder

```shell
mkdir myproj && cd myproj
```

## Add .gitignore and init git repository

Add the following .gitignore

```shell
.venv
*.sqlite3
__pycache__
```

Init repo with

```shell
git init
git add . && git commit -m "first commit"
```

## Create virtual environment for Python and activate it

```shell
py -m venv .venv
source .venv/bin/activate
```

## Install django

```shell
py -m pip install django
```