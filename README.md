Exercise: Requests
wincpy start cc1b724762854e85a8defa04287f708b

For this exercise, you will need to read Flask's documentation:

Flask -- Quickstart
Create a Flask application that can be run as follows:

export FLASK_APP=main.py
flask run
It should then serve content according to the specifications in this table:

method	path	expected response content
GET	/	<p>Home, sweet home.</p>
GET	/greet	<h1>Hello, world!</h1>
GET	/greet/<example_name>	<h1>Hello, example_name!</h1>
You can test your implementation with the pytest, which runs the test in the test_main.py file we supplied with wincpy start.
