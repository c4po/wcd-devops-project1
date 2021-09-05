# wcd-devops-project1

Install and run a test python(flask) application on local machine

* create a Python virtual environment
  Using a virtual environment allows you to manage your project’s dependencies without messing with system-level files shared by all applications. Run the following commands to create and activate a virtual environment for your application.

```shell
$ python3 -m venv venv
$ source venv/bin/activate
```

* install Flask python package and capture the version or install the package defined in the `requirements.txt` file

```shell
$ python3 -m pip install Flask
$ python3 -m pip freeze > requirements.txt
### or ###
$ python3 -m pip install -r requirements.txt
```

* start the application

```shell
$ export FLASK_APP=hello
$ flash run
```

