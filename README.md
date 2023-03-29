# Finance

Finance is a web application that allows users to buy and sell stocks and keep track of their portfolio. 

## Usage

1. Clone the repository.
2. Install the required packages by running `pip install -r requirements.txt`.
3. Set the `FLASK_APP` environment variable to `application.py`.
4. Run `flask run` to start the server.
5. Open `http://localhost:5000` in your web browser to use the application.

## Files

- `application.py`: Flask application that runs the web application.
- `helpers.py`: Helper functions for the application.
- `requirements.txt`: List of Python packages required to run the application.
- `templates/`: Directory containing HTML templates for the application.
- `static/`: Directory containing CSS and JS files for the application.

## Features

- Register a new account.
- Log in with an existing account.
- Search for stock prices using stock symbols.
- Buy and sell stocks.
- View transaction history.
- View current portfolio.
- Change account password.

## Technology

- Flask: Python web framework used to build the application.
- SQLite: Database used to store user information, transaction history, and portfolio information.
- Bootstrap: Front-end framework used for styling the application.

## Credits

This project was completed as part of the [CS50x](https://cs50.harvard.edu/x/2021/) course offered by Harvard University. The `helpers.py` file was provided by the course staff as a starting point for the application.

