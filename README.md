# localhost-server
making simple localhost server using flask and python3
(i'm here using Ubuntu OS)
the steps for this :
(In Ubuntu, python 3 is among the default, so no need to install it, just check the version using terminal)
1)$ sudo apt install python3-venv
2)$ mkdir my_flask_app
3)$ cd my_flask_app
4)$ python3 -m venv venv
5)$ source venv/bin/activate
6)(venv)$ pip3 install Flask
7)(venv)$ python3 -m flask --version
8)(venv)$ export FLASK_APP=hello
9)(venv)$ flask run
10)type http://localhost:8080
