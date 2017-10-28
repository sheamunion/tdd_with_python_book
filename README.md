# tdd_with_python_book

## Dependencies

* Python 3.6
* [Selenium 3.6.0](https://pypi.python.org/pypi/selenium)
* [Chromedriver](https://sites.google.com/a/chromium.org/chromedriver/downloads)

After installing chromedriver, be sure to add it to your PATH.

```
exports PATH=$PATH:/path/to/chromedriver
```

## Starting the app

From Django project root, the `superlists` directory, make migrations and migrate:

```
python3 manage.py makemigrations
python3 manage.py migrate
```

Run the server:

```
python3 manage.py runserver
```

Navigate to [http://localhost:8000](http://localhost:8000).

## Run all the tests

From the Django project root:

```
python3 manage.py test
```

## Run the functional tests

```
python3 manage.py test functional_tests
```

## Run the unit tests

```
python3 manage.py test lists
```


