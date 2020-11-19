# PostgreSQL Basics with Psycopg2

A Jupter [notebook][1] that demonstrates how [Psycopg2][2] can be used to operate [PostgreSQL][3] databases.

Psycopg is *"the most popular PostgreSQL adapter for the Python programming language"*.

## Prerequisites

- [PostgreSQL][3].

## Getting Started

1. Download the files, and create a virtual environment to work in.

    ```bash
    git clone https://github.com/Tim-Abwao/Psycopg2-Basics.git
    cd Psycopg2-Basics
    python3 -m venv venv
    source venv/bin/activate
    ```

2. Install the required packages.  Please visit the [Psycopg2 installation page][4] for an in-depth guide on how to resolve some essential dependencies if any issues arise.

    ```bash
    pip install psycopg2 pandas notebook
    ```

3. Launch the notebook server:

    ```bash
    jupyter notebook 'Psycopg2 Basics.ipynb'
    ```

[1]: Psycopg2%20Basics.ipynb
[2]: https://www.psycopg.org/
[3]: https://www.postgresql.org
[4]: https://www.psycopg.org/docs/install.html
