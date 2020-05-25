# PostgreSQL Basics with Psycopg2

A Jupter notebook that demonstrates how [Psycopg2](http://initd.org/psycopg/) can be used to operate  [PostgreSQL](https://www.postgresql.org) databases.

Psycopg is "*the most popular PostgreSQL adapter for the Python programming language*".

## Prerequisites

- [PostgreSQL](https://www.postgresql.org/download/).
- Python.

## Getting Started
Please visit the [Psycopg2 installation page](https://www.psycopg.org/docs/install.html#install-from-source) for an in-depth guide on how to resolve dependencies before installing it.

Afterwards,

- Download the files, and create a virtual environment to work in:

```bash
git clone https://github.com/Tim-Abwao/Psycopg2-Basics.git
cd Psycopg2-Basics
python3 -m venv env
source env/bin/activate
```

- Install the required packages:

```bash
pip install psycopg2 pandas notebook
```

- Finally, launch the notebook:

```bash
jupyter notebook 'PostgreSQL Basics with Psycopg2.ipynb'
```
