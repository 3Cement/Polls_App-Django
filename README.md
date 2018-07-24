# Polls App-Django
This is a simple polls app created with tutorial from django documentation to learn Django framework.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Existing Example
Existing example is hosted on Heroku and you can check at the following link:
https://shielded-anchorage-53647.herokuapp.com/

### Prerequisites

What things you need to install the software and how to install them

```
1. Create your virtual environment
2. Clone this repository
3. Initialize database
4. Run Polls App
```

### Installing and deployment

A step by step series of examples that tell you how to get a development env running

1. Create new virtual environment, for example with virtualenvwrapper:

```
$ pip install virtualenvwrapper
$ mkvirtualenv example_venv
```

2. Clone this repository:

```
$ git clone https://github.com/3Cement/Polls_App-Django
```
2.1. Change you time zone in settings.py if you are in different one than Europe/London

```
TIME_ZONE = 'Europe/London'
```
3. Initialize database

```
$ python3 manage.py makemigrations
$ python3 manage.py migrate
```

4. Run Polls App (in folder with manage.py file):

```
$ python manage.py runserver
```
## Screenshots

## Running the tests
```
$ python manage.py test
```

## Built With

## Contributing

## Authors

* **Daniel Milewski** - https://github.com/3Cement

See also the list of [contributors](https://github.com/3Cement/Polls_App-Django/graphs/contributors) who participated in this project.

## License

This project is licensed under the Apache License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
