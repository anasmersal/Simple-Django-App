# Django Project Overview

## Description

This Django project showcases a simple web application with functionalities including:

- Rendering static HTML pages (`index.html`, `about.html`).
- Handling form submissions (`BookingForm`) and storing valid data.
- Displaying menu data and specific menu items.

## Views

- `home`: Renders the home page.
- `about`: Renders the about page.
- `book`: Handles form submissions and stores data.
- `menu`: Displays all menu data.
- `display_menu_item`: Shows a specific menu item.

## Structure

- `views.py`: Contains view functions for handling HTTP requests.
- `.forms`: Includes form definitions.
- `.models`: Contains the data model definitions.

## Setup & Usage

- Install Django (`pip install django`).
- Clone the repository.
- Run migrations (`python manage.py makemigrations` and `python manage.py migrate`).
- Start the server (`python manage.py runserver`).

- Access different views:
  - Home: `/`
  - About: `/about/`
  - Booking: `/book/`
  - Menu: `/menu/`
  - Display Menu Item: `/menu/{pk}/`
