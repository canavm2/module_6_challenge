# module_6_challenge

The module 6 challenge for fintech course

The Jupyter Lab file follows along as an exercise to analyze risk and reward, following statistics like standard deviation, shapre ratio and beta.

---

## Technologies

The sheet requires Pandas for analyzing data frames in jupyter labs.
It requires Jupyter Labs for a user interface.
It requires Path from pathlib to help read .csv files.
A custom python package MCForecastTools is used by the sheet.

An alpaca account and API key is required.

---

## Installation Guide

Other than Python 3.7, no installation is necessary, Jupyter Labs runs in a browser, including Chrome.  Launch the file by navigating to the directory of the file through a CLI and then running Jupyter labs, with "jupyter lab".

Create an alpaca account here: [Alpaca Homepage](https://alpaca.markets/)
Once you have an account use the account information to create and record an Alpaca API key and Secret Key.  Follow instructions to copy these keys into a ".env" file, which is not included with the repository since it contains sensitive data.

The custom python package MCForecastTools is included with the sheets and is required for many of the monte carlo simulations.


---

## Usage

The worksheet runs through a scenario and teaches the user to import market data from the Alpaca API.

![Image of jupyter lab](jupyter_lab_image.PNG)

---

## Contributors

Michael Canavan

---

## License

the content of the course is owned and managed by UC Berkeley Fintech Bootcamp.