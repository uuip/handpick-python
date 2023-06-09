## Short and handpick Python packages list.

### Package Management

* poetry
  - poetry self add poetry-plugin-up
* pipdeptree

### Code Formatter

* black
* pylint

### Interactive Interpreter

* ipython

### System Utilities

* psutil

### Date and Time

* arrow
* tzdata

### Logging

* loguru
* concurrent-log-handler

### Serialization

* ujson
* pyyaml

### File Processing

* xlwings - interactive operation with excel
* pyexcel - base on openpyxl
* openpyxl - pandas's default excel engine
* xlsxwriter - write faster than openpyxl, can be set as pandas's excel writing engine
* python-magic - identify file types

### Web

* requests
* pysocks - support socks5 for requests
* httpx
* bs4, beautifulsoup4

### Selenium

* playwright
* selenium
* selenium-wire
* webdriver-manager

### Async

* uvloop
* gevent
* psycogreen
* nest-asyncio

### Django

* django
* django-filter
* django-redis
* django-celery-beat
* django-sql-explorer
* django-guardian
* django-import-export
* django-model-utils
  - SoftDeletableModel
* django-raw-sugar
  - turns your raw sql into a QuerySet.
* django-netfields
* django-queryable-properties
* django-extensions
  - python3 manage.py shell_plus --lab --no-browser
  - python3 manage.py shell_plus --print-sql –truncate-sql 0
* django-silk
  - profiling and inspection tool
* django-simpleui
  - django admin theme
* djangorestframework
* djangorestframework-simplejwt
* pyjwt
* gunicorn

### Fastapi

* fastapi
* tortoise-orm = { extras = ["accel", "asyncpg"], version = ">=0.19.3" }
* pydantic = { extras = ["dotenv"], version = ">=1.10.7" }
* uvicorn

### JupyterLab

* django-extensions
* jupyterlab
* jupyterlab-lsp
* importlib-resources = { version = "^5.7.1", python = "3.8" }
* python-lsp-server = { extras = ["all"], version = "^1.4.1" }
* jedi = "<0.18.0" # python-lsp-server depend on specific version

### Database

* asyncpg
* psycopg2 #apt install libpq-dev
* redis
* hiredis
* aioredis
* aiosqlite
* DBUtils

### ORM

* peewee
* sqlalchemy

### Job Scheduler

* apscheduler
* celery

### Data Factories

* model-bakery
* factory-boy
* faker

### Shell

* click
* fire
* rich
* tqdm
* prettytable

### Algorithms

* pyahocorasick

### Cryptography

* cryptography
* pycryptodome

### Data Analysis

* bottleneck
* numpy
* pyarrow
* pandas
* dask = { extras = ["diagnostics", "distributed"], version = ">=2023.4.1" }
* polars


