Via linux ubuntu 22.04 server and python 3.10.6

How to install the application:

$ sudo apt update
$ sudo apt -y upgrade
$ sudo apt install -y python3-pip
$ sudo apt install -y build-essential libssl-dev libffi-dev python3-dev
$ sudo apt install -y python3-venv
$ mkdir reserveringssysteem
$ cd reserveringssysteem
$ python3 -m venv env
$ ls env
$ source env/bin/activate
$ pip install flask
$ python init_db.py
$ export FLASK_APP=app
$ export FLASK_ENV=development
$ flask run

How to start the application:

$ cd Reserveringssysteemp2
$ python3 -m venv env
$ source env/bin/activate
$ pip install flask
$ export FLASK_APP=app
$ flask run
