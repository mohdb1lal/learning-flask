# FLASK
## I am learning how to use flask
#### This is a demo project to microblog website
###### (Thursday-24/07/25)
admin@MB-2 learning-flask % python3 -m venv venv; . venv/bin/activate 
(venv) admin@MB-2 learning-flask % mkdir microblog
(venv) admin@MB-2 learning-flask % cd microblog
(venv) admin@MB-2 microblog %  pip install flask
Collecting flask
  Downloading flask-3.1.1-py3-none-any.whl.metadata (3.0 kB)
Collecting blinker>=1.9.0 (from flask)
  Using cached blinker-1.9.0-py3-none-any.whl.metadata (1.6 kB)
Collecting click>=8.1.3 (from flask)
  Downloading click-8.2.1-py3-none-any.whl.metadata (2.5 kB)
Collecting itsdangerous>=2.2.0 (from flask)
  Using cached itsdangerous-2.2.0-py3-none-any.whl.metadata (1.9 kB)
Collecting jinja2>=3.1.2 (from flask)
  Downloading jinja2-3.1.6-py3-none-any.whl.metadata (2.9 kB)
Collecting markupsafe>=2.1.1 (from flask)
  Downloading MarkupSafe-3.0.2-cp313-cp313-macosx_11_0_arm64.whl.metadata (4.0 kB)
Collecting werkzeug>=3.1.0 (from flask)
  Using cached werkzeug-3.1.3-py3-none-any.whl.metadata (3.7 kB)
Downloading flask-3.1.1-py3-none-any.whl (103 kB)
Using cached blinker-1.9.0-py3-none-any.whl (8.5 kB)
Downloading click-8.2.1-py3-none-any.whl (102 kB)
Using cached itsdangerous-2.2.0-py3-none-any.whl (16 kB)
Downloading jinja2-3.1.6-py3-none-any.whl (134 kB)
Downloading MarkupSafe-3.0.2-cp313-cp313-macosx_11_0_arm64.whl (12 kB)
Using cached werkzeug-3.1.3-py3-none-any.whl (224 kB)
Installing collected packages: markupsafe, itsdangerous, click, blinker, werkzeug, jinja2, flask
Successfully installed blinker-1.9.0 click-8.2.1 flask-3.1.1 itsdangerous-2.2.0 jinja2-3.1.6 markupsafe-3.0.2 werkzeug-3.1.3
(venv) admin@MB-2 microblog % mkdir app && cd app;
(venv) admin@MB-2 app % touch __init__.py
(venv) admin@MB-2 app % touch routes.py  
(venv) admin@MB-2 app % cd . && pwd
/Users/admin/My Projects/learning-flask/microblog/app
(venv) admin@MB-2 app % cd .. && pwd
/Users/admin/My Projects/learning-flask/microblog
(venv) admin@MB-2 microblog % export FLASK_APP=microblog.py
(venv) admin@MB-2 microblog % flask run
 * Serving Flask app 'microblog.py'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on http://127.0.0.1:5000
Press CTRL+C to quit
127.0.0.1 - - [24/Jul/2025 15:49:26] "GET / HTTP/1.1" 200 -
127.0.0.1 - - [24/Jul/2025 15:49:26] "GET /favicon.ico HTTP/1.1" 404 -
^C%                                                                                                                       
(venv) admin@MB-2 microblog % 
---
export FLASK_APP=microblog.py
---
