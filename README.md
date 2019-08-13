# Catalog Restaurant Application - Udacity Full Stack Web Developer Nanodegree

## Overview 
This is a catalog project that stores and shows Restaurant Menu information.

The catalog has menu categories and food items.

Each category has a name and a description.

Each item has a name, a description and is related to a category.

## Set Up / Requirements 
To run this catalog, the following software and libraries are necessary:

* PostgreSQL - installation instructions [here](https://www.postgresql.org/docs/9.3/installation.html)

* Python 2.7 - installation instructions [here](https://www.python.org/downloads/)

* Additional Python libraries:
    * flask - installation instructions [here](http://flask.pocoo.org/docs/1.0/installation/)
    * oauth2client.client - installation instructions [here](https://oauth2client.readthedocs.io/en/latest/)
    * requests - installation instructions [here](https://2.python-requests.org//en/v2.7.0/user/install/)
    * sqlalchemy - installation instructions [here](https://pypi.org/project/SQLAlchemy/)

**Alternative to download:** Run ``pg_config.sh`` to install or update necessary software and libraries.

## How to run this project

A database is necessary to run this project.

To create the database, run:

``` 
$ python database_setup.py 
```

To create some initial data in the database, run:

```
$ python lotsofmenus.py 
```

To start the server, run:

```
$ python application.py
```

To access the application, open a browser and type:

http://localhost:4996

## Catalog Functionalities

### Json catalog

Visit [this page](http://localhost:4996/restaurant/JSON) to see a json list of all restaurants in the catalog.

### List Categories
Go to [this page](http://localhost:4996/restaurant/) to see all categories and the most recent added items.

### List items of a given category
From the initial category page, select the desired category and it will show all items of that category.

### IMPORTANT: Google authentication
In order to modify information you must log in using Google or Facebook authentication. Authenticated users have the ability to post, edit, and delete their own items.

### Create new items
You can create new items related to the existing categories.

### Edit items
You can change name and description of a given item.

### Delete items
You can delete an item.
