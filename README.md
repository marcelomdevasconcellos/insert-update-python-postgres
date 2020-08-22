# insert-update-python-postgres
Insert and update data from postgres tables between different databases on python

1) Create env_example based .env;

```
DATABASE_SOURCE=psql://user:pass@host:port/name
DATABASE=psql://user:pass@host:port/name
TABLES=database1,database2,database3,...,databaseN
```

* Configure source database in DATABASE_SOURCE variable;
* Configure destiny database in DATABASE variable;
* Configure tablenames in TABLES variable;

2) Install django-environ: 

```
pip install -r requirements.txt
```

3) Execute: 

```
python copy.py
```

