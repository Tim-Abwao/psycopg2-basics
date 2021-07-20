# Psycopg2 Basics

A [Jupyter notebook][1] that demonstrates how [Psycopg2][2] can be used to operate [PostgreSQL][3] databases.

Psycopg is *"the most popular PostgreSQL adapter for the Python programming language"*.

## Prerequisites

- [PostgreSQL][3].

## Getting Started

1. Download the files, and create a virtual environment to work in.

    ```bash
    git clone https://github.com/Tim-Abwao/psycopg2-basics.git
    cd psycopg2-basics
    python3 -m venv venv
    source venv/bin/activate
    ```

2. Install the required packages.  Please visit the [Psycopg2 installation page][4] for an in-depth guide on how to resolve some essential dependencies if any issues arise.

    ```bash
    pip install -U pip
    pip install -r requirements.txt
    ```

3. Launch the notebook server:

    ```bash
    jupyter notebook psycopg2_basics.ipynb
    ```

[1]: psycopg2_basics.ipynb
[2]: https://www.psycopg.org/
[3]: https://www.postgresql.org
[4]: https://www.psycopg.org/docs/install.html
