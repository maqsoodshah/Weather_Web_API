## Flask Weather App

A web application to display the current weather in your cities using openweathermap api, built with Python, Flask, SQLAlchemy, SQLite, HTML, and Bulma template.

This project is intended to learn about [openweathermap.org](https://openweathermap.org/) using web development with Python and Flask.

## Project Status
This project is currently in development. Future updates wil include clickable tiles for time, news, etc.

#### Example:   
![Image description](https://github.com/maqsoodshah/Weather_Web_API/blob/master/images/weather_app.PNG)

## Installation and Setup Instructions

Clone this repository. You will need `python`, `virtualenv`, and `virtualenvwrapper-win` installed on your machine.

#### Set up a virtual environment:

`mkvirtualenv weather_api`

#### Installation:

`pip install flask`

`pip install flask_sqlalchemy`

`pip install requests`   

#### To Start Server:

`flask run` 

or to run on specific host/port

`flask run -h 1.1.1.1 -p 1111` 
