# PostgreSQL Basics with Psycopg2
A Jupter notebook to run a few of [PostgreSQL](https://www.postgresql.org)'s commands and SQL queries, in Python, using [Psycopg2](http://initd.org/psycopg/). 

Psycopg is "*the most popular PostgreSQL adapter for the Python programming language*".

# Prerequisites
- You'll need to have [PostgreSQL](https://www.postgresql.org/download/) and Python installed.
- Please visit the [Psycopg2 installation page](https://www.psycopg.org/docs/install.html#install-from-source) for help on how to resolve all dependencies before installing it.

# Getting Started
1. Download the files, then create a virtual environment to work in:
```bash
git clone https://github.com/Tim-Abwao/Psycopg2-Basics.git
cd Psycopg2-Basics
python3 -m venv venv
source venv/bin/activate
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Finally, launch the notebook:
```bash
jupyter notebook 'PostgreSQL Basics with Psycopg2.ipynb'
```
