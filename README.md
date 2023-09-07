## Short and handpick Python packages list.

### Package Management

* poetry
  - poetry self add poetry-plugin-up

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
* nest-asyncio
* asyncstdlib
* aiostream
* pytest-asyncio

### Django

* django
* django-filter
* django-redis
* django-sql-explorer
* django-import-export
* django-model-utils
  - SoftDeletableModel
* django-raw-sugar
  - turns your raw sql into a QuerySet.
* djangorestframework
* djangorestframework-simplejwt
* pyjwt
* gunicorn

* django-netfields
* django-queryable-properties
* django-shared-property
* django-guardian
* django-silk
  - profiling and inspection tool
* django-simpleui
  - django admin theme

### Lock
* PALs
* django_pglocks

### Fastapi

* fastapi
* pydantic = "^2.3.0"
* pydantic-settings = "^2.0.3"
* uvicorn

### JupyterLab

* jupyterlab
* jupyterlab-lsp
* python-lsp-server = { extras = ["all"], version = "^1.4.1" }
* jedi = "<0.18.0" # python-lsp-server depend on specific version
* django-extensions
  - python3 manage.py shell_plus --lab --no-browser

### Database

* asyncpg
* psycopg
* redis
* hiredis
* aiosqlite

### ORM

* peewee
* sqlalchemy

### Job Scheduler

* apscheduler
* celery
* django-celery-beat

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


