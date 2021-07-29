# Project Description
This project is a homework assignment to teach how to get Pycharm setup with Docker, Flask, MYSQL

* This project have Docker Compose setup, a python flask app and a mysql server that will load data from the db/init.sql file.
* The first time the database starts (note you will need to do a docker down by right clicking on the compose file in pycharm docker service to reset the database if you make any   changes to the sql statements that load initially, it doesn’t run the init.sql each time you run your project, just each time docker-compose is run from scratch). 
* Then you need to create a flask framework to serve flask jinja template files and send http POST requests to update, add new records, and delete.

# Assignment
[Here is the Example of ADD, VIEW, UPDATE, DELETE](https://github.com/Yash-2903/PythonFlaskWithMySQLAllTemplates/blob/master/Homework%205.pdf)

# Reading

[Jinja Templates](https://realpython.com/primer-on-jinja-templating)

[SQL Connection](https://www.w3schools.com/python/python_mysql_getstarted.asp) 

[Getting started and Reference for Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

[Tutorials templates](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-ii-templates)

[Documentation for Flask Templates](https://flask.palletsprojects.com/en/1.1.x/tutorial/templates/)

# Useful Links

* [Flask Homepage and Documentation](https://flask.palletsprojects.com/en/1.1.x/)
* [JSON Spec Reference](https://www.json.org/json-en.html)
* [SimpleJSON Reference](https://simplejson.readthedocs.io/en/latest/)
* [W3 Schools SQL Tutorial and Reference](https://www.w3schools.com/sql/)
