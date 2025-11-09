# weather-app
When a user enters the name of a city, the Weather App retrieves current weather information. It provides temperature, humidity, condition (such as clear or rainy), and wind speed by integrating Django with external APIs like OpenWeatherMap.


Required Modules or Packages:
Python 3.8+: Make sure you have Python version 3.8 or higher installed on your system.

Django 3.x or 4.x: You’ll need the Django framework, version 3.x or 4.x, to build and run the system.

pip: This is the Python package manager that you’ll use to install the required libraries and packages.

You can install the core requirements with:

pip install django
Or install from a requirements.txt:
pip install -r requirements.txt
How to Run the Code:
Follow these steps to launch the application locally:

✅ STEP 1: Download or Clone the Project

Option A: If you have a ZIP file

1. Extract it to a folder.

2. Open that folder in VS Code:

VS Code → File → Open Folder…

Option B: If using Git clone

git clone https://github.com/username/repository-name.git

cd repository-name
code .

✅ STEP 2: Set Up Virtual Environment

This keeps your project dependencies isolated.

# Create virtual environment (in project folder)
python -m venv venv

# Activate it:

# On Windows:

venv\Scripts\activate

# On macOS/Linux:

source venv/bin/activate

✅ STEP 3: Install Requirements

Most Django projects have a requirements.txt file. Install the packages:

pip install -r requirements.txt

If requirements.txt is missing, you can manually install Django:

pip install django

✅ STEP 4: Configure .env or Settings (If Required)

Some projects require .env files (for secret keys or DB settings).

Check the README or .env.example if present, and create your own .env.

✅ STEP 5: Run Migrations

python manage.py makemigrations

python manage.py migrate

✅ STEP 6: Create Superuser (for Admin Login)

python manage.py createsuperuser

Follow the prompts.

✅ STEP 7: Run the Django Development Server

python manage.py runserver
Open http://127.0.0.1:8000 in your browser.


# learn python frameworks by making weather app
weather app using different python framework

![]([weather-app](https://img.shields.io/github/repo-size/DipakLande/weather-app.svg?label=Repo%20size&style=flat-square))&nbsp;
[![Made with python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://github.com/DipakLande)

> Django

Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It's free and open source.

<a href="https://github.com/DipakLande/weather-app/tree/2cb3c4ebc1f1b3325d87687a0a139ff6a7b074dd/weather-app/weather-django" >project link </a>

>flask

Flask is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

<a href="https://github.com/DipakLande/weather-app/tree/2cb3c4ebc1f1b3325d87687a0a139ff6a7b074dd/weather-app/weather-flask" >project link </a>

>tkinter

Python offers multiple options for developing GUI (Graphical User Interface). Out of all the GUI methods, tkinter is the most commonly used method. It is a standard Python interface to the Tk GUI toolkit shipped with Python. Python with tkinter outputs the fastest and easiest way to create the GUI applications.

<a href="https://github.com/DipakLande/weather-app/tree/2cb3c4ebc1f1b3325d87687a0a139ff6a7b074dd/weather-app/weather-tkinter" >project link </a>

---

## Virtualenv & Dependencies
### create a virtualenv and run requirements.txt<br/>

<b> what is virtual environment ? </b><br/>
A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them. This is one of the most important tools that most of the Python developers use.
<br/>
<a href="https://www.geeksforgeeks.org/python-virtual-environment/" >read more... </a>

- <b>installing virtualenv</b>
<pre>$ pip install virtualenv</pre>

- <b>creating virtualenv</b>
<pre>$ virtualenv env</pre>
env is name of environment

- <b>activating virtual environment</b>
<pre>$ source env/bin/activate </pre>

- <b>run requirements.txt</b>
<pre>$ pip install -r requirements.txt</pre>

Note: each application contains its own requirements

---


<strong>made by Dipak_Lande with 💕 and 🍺</strong>





