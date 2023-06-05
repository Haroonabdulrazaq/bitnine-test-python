# Bitnine Challenge

This is a simple application which demostrate how to connect to a PostgreSQL DB. It's a Challenge by Bitnine.

The application returns data that was inserted in the user_table as a json_data with a status code of 200, if the call to index<code>/</code> is successfull
and it throws an exception of with a status code of 500, if there is an error.

## Available Endpoint

- http://localhost:3000/

Returns

```
{"data":[{"age":"34","name":"Jenny","phone":null,"user_id":"3"},{"age":"29","name":"Tom","phone":"1-800-123-1234","user_id":"2"},{"age":"28","name":"John","phone":null,"user_id":"1"}],"status_code":200}
```

## Environment/Packages

- python 3.11.0
- Flask
- PostgreSQL 15
- SQLALCHEMY

## DEV Configuration

- Create a config.py file and Add the following credentials

```DB_HOST = ""
 DB_PORT =
 DB_NAME = ""
 DB_USER = ""
 DB_PASSWORD = ""
```

## How to use

- Clone the code from [here]('https://github.com/Haroonabdulrazaq/bitnine-test-python.git)
- install all the packages in <code>requirements.txt</code> file
- Run <code>python postgres_driver.py</code>
