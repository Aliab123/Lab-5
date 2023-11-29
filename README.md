# Hello World Django App

This Django application displays a simple "Hello World" message in JSON format.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Python 3.x installed on your machine
- Django installed (you can install it using `pip install django`)

## Installation

To install the Hello World Django app, follow these steps:

1. Clone the repository to your local machine or download the source code.
2. Navigate to the project directory (e.g., `cd helloworld_project`).

## Running the Application

To run the Django app, follow these steps:

1. Inside the project directory, run the command `python manage.py runserver`.
2. This will start the Django development server.

## Accessing the Hello World JSON Response

Once the server is running, you can access the Hello World JSON response by:

1. Opening a web browser.
2. Navigating to `http://127.0.0.1:8000/hello/`.
3. You should see the JSON response `{"Message": "Hello World!"}` displayed in your browser.

## Additional Information

- Ensure that the Django project's URL configuration (`helloworld_project/urls.py`) and the application's URL configuration (`hello/urls.py`) are properly set up.
- If you encounter any issues, check that Django is installed correctly and that the server is running without errors.

