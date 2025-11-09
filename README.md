# Weather-App-Using-Django
When a user enters the name of a city, the Weather App retrieves current weather information. It provides temperature, humidity, condition (such as clear or rainy), and wind speed by integrating Django with external APIs like OpenWeatherMap.

Required Modules or Packages: Python 3.8+: Make sure you have Python version 3.8 or higher installed on your system.

Django 3.x or 4.x: You’ll need the Django framework, version 3.x or 4.x, to build and run the system.

pip: This is the Python package manager that you’ll use to install the required libraries and packages.

You can install the core requirements with:

pip install django Or install from a requirements.txt: pip install -r requirements.txt How to Run the Code: Follow these steps to launch the application locally:

✅ STEP 1: Download or Clone the Project

Option A: If you have a ZIP file

Extract it to a folder.

Open that folder in VS Code:

VS Code → File → Open Folder…

Option B: If using Git clone

git clone https://github.com/username/repository-name.git

cd repository-name code .

✅ STEP 2: Set Up Virtual Environment

This keeps your project dependencies isolated.

Create virtual environment (in project folder)
python -m venv venv

Activate it:
On Windows:
venv\Scripts\activate

On macOS/Linux:
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

python manage.py runserver Open http://127.0.0.1:8000 in your browser.
