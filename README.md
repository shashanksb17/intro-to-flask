# Flask Applications

This repository contains two Flask applications: a basic Flask application and a CRUD (Create, Read, Update, Delete) application.

## Basic Flask Application

The basic Flask application demonstrates the usage of Flask to create a simple web application. It includes three routes:

- `/`: Displays a welcome message.
- `/greet/<username>`: Greets the user specified in the `<username>` parameter.
- `/farewell/<username>`: Bids farewell to the user specified in the `<username>` parameter.

To run the basic Flask application:

1. Install Flask by running `pip install flask`.
2. Run the application by executing `python app.py`.
3. Open your web browser and visit `http://127.0.0.1:5000/` to access the application.

## CRUD Application

The CRUD application is a basic Flask application that allows you to perform Create, Read, Update, and Delete operations on a Python dictionary. It includes the following routes:

- `/create`: Displays a form where you can input data to create a new entry in the dictionary.
- `/read`: Displays the current state of the dictionary.
- `/update`: Displays a form where you can update the value of an existing entry in the dictionary.
- `/delete`: Displays a form where you can delete an existing entry from the dictionary.

To run the CRUD application:

1. Install Flask by running `pip install flask`.
2. Run the application by executing `python app.py`.
3. Open your web browser and visit `http://127.0.0.1:5000/` to access the application.
4. Use the provided forms to interact with the dictionary.

Please note that these applications are for learning purposes and do not use a database. Data is stored in memory and will be lost when the applications are restarted.

Feel free to explore and modify the applications according to your needs!


