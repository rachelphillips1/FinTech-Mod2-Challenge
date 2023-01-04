# Loan Qualifier App

This is a command-line interface application which allows a user to determine at which banks, if any, their loan request may qualify based on their credit score, monthly debt, monthly income, desired loan amount, and home value. Any qualifying banks can be saved as a CSV file.

---

## Technologies

Languages:
* Python 3.7

Packages:
* Fire - For the command line interface, help page, and entry-point.
* Questionary - For interactive user propmpts and dialogs.
* CSV - To acess data from and write data to a csv file.
* Path - To allow the user to specify the locations of csv files.


---

## Installation Guide

Before runningg the application first install the followig dependencies.

'''python
pip install fire
pip install questionary
'''

---

## Usage

To use the loan qualifier application, simply clone the repository and run the **app.py** file. You will be prompted to enter a path to the latest banking data, and then asked for your financial information.

'''python
python app.py
'''

---

## Contributors

This project was completed as part of the FinTech Bootcamp at UC Berkeley Extension. Code contributions were made by myself in addition to the code provided by the program.

---

## License

MIT
