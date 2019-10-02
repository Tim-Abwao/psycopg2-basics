# PostgreSQL Basics with Psycopg2
A jupter notebook to explore some of [PostgreSQL](https://www.postgresql.org)'s common features. [Psycopg2](http://initd.org/psycopg/) is "the most popular PostgreSQL adapter for the Python programming language".

## Prerequisites
- You'll have to have *both* PostgreSQL and Python installed.
- Some experience with **PostgreSQL**. PostgreSQL's [manual](https://www.postgresql.org/docs/) has a [tutorial](https://www.postgresql.org/docs/11/tutorial.html), which is a great place for beginners to get started.
- Experience with **Python**, particularly `pip`, **pandas** and **Jupyter notebooks**.


1. Create a virtual environment (to avoid altering your system's Python state)
```
python3 -m venv venv
source venv/bin/activate
```
or for **Windows**
```
py -3 -m venv venv
venv\Scripts\activate
```
2. Install the required packages
```
pip install -r requirements.txt
```
3. Finally, launch the notebook
```
jupyter notebook 'PostgreSQL Basics with Psycopg2.ipynb'
```
