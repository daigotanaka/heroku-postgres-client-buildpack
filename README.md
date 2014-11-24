# Heroku PostgreSQL Buildpack

Build PostgreSQL client on Cedar app

**This does not work yet. Sorry!**

## Usage

Push the app to Heroku and run our executable:

```bash
$ heroku create --buildpack https://github.com/daigotanaka/postgresql-buildpack.git
$ git push heroku master
```

## Motivation

To be used with R buildpack that executes RPostgresSQL package.
