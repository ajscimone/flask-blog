# flask-blog

On windows, you must set flask in the environment using:
"set FLASK_APP=flaskblog.py"

Then you can run the program with:
"flask run"

You can also run it with python
"python flaskblog.py"


In order to create the database, open python in the directory of the project and run the following commands:
"from flaskblog import db"
"db.create_all()"