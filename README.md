windows

1. terminal: clone/pull the repository
2. terminal: cd data_cleaning
3. terminal: python3 venv .venv
4. terminal: .venv/Scripts/activate
5. terminal: use pip3 to install:
    - jupyter
    - pandas
    - sqlalchemy
    - seaborn
    - mysqlclient
    - mysqlclient
    - openpyxl
6. if you want to also store the data in a local mysql database, the you need to
    - update `db_conn_str` variable in the code to match your local mysql setup
7. terminal: jupyter lab