windows

1.  terminal: clone/pull the repository
2.  terminal: `cd data_analysis_sample_work`
3.  terminal: `python3 -m venv .venv`
4.  terminal: `.venv/Scripts/activate`
5.  terminal: use pip3 to install: `pip3 install package1 package2 ... packageN`
    - jupyter
    - jupyterlab
    - pandas
    - sqlalchemy
    - seaborn
    - mysqlclient
    - openpyxl
6.  if you want to also store the data in a local mysql database, <br>
    then you need to update `db_conn_str` variable in the code to match your local mysql setup;<br>
    if not, you can just comment out the code block resplonsible for saving the data tables to a local mysql database.
7.  terminal: `jupyter lab`
8.  browser: `http://localhost:8888/lab`