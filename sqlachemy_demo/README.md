# SQLAlchemy workshop

An interactive workshop for SQLAlchemy

Showing how to use the library and what it does compared to sql

## Setup

```
python -m virtualenv .venv
.venv\bin\activate
pip install -r requirements.txt
```

Create a credentials file called `credentials.json` inside this directory:

If you use postgres defaults, it will contain these:
```
{
    "username": "postgres",
    "password": "postgres",
    "host": "localhost",
    "default-database": "postgres"
}
```