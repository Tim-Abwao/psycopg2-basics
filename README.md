# PostgreSQL Basics with Psycopg2

A Jupter notebook that demonstrates how [Psycopg2][1] can be used to operate [PostgreSQL][2] databases.

Psycopg is *"the most popular PostgreSQL adapter for the Python programming language"*.

## Prerequisites

- [PostgreSQL][2].
- Python.

## Getting Started

Please visit the [Psycopg2 installation page][3] for an in-depth guide on how to resolve some essential dependencies before installing it.

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

- And finally, launch and explore the notebook:

    ```bash
    jupyter notebook 'PostgreSQL Basics with Psycopg2.ipynb'
    ```

That's all.

[1]: https://www.psycopg.org/
[2]: https://www.postgresql.org
[3]: https://www.psycopg.org/docs/install.html#install-from-source
