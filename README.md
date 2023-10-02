# Django_React_Vite_Auth
Django Serving up React application produced in Vite for session based authentication 
A web application template built with Django, React, and Vite, featuring session-based authentication.

This is part of my YouTube Channel [BekBrace] project.

Code in the repo is provided for both the frontend and the backend

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This web application template combines the power of Django, React, and Vite to provide a robust and modern web development stack. It includes session-based authentication, allowing users to sign in, access protected routes, and interact with the application securely.

## Features

- User authentication with session-based login/logout.
- React-based frontend powered by Vite for fast development and building.
- Django backend with customizable authentication and API endpoints.
- Protected routes to ensure secure access to authenticated users.
- Easy-to-configure setup for both development and production environments.

## Prerequisites

Before getting started, ensure you have the following prerequisites installed:

- [Python](https://www.python.org/downloads/) (version x.x.x)
- [Node.js](https://nodejs.org/en/download/) (version x.x.x)
- [Django](https://docs.djangoproject.com/en/stable/intro/install/) (version x.x.x)
- [Vite](https://vitejs.dev/guide/#scaffolding-your-first-vite-project) (version x.x.x)
- [Your Other Dependencies](#your-other-dependencies)

## Getting Started

Follow these steps to set up the project locally:

### Installation

1. Clone the repository:

   ```bash
   git clone 
   cd your-project

cd backend
python -m venv venv
source venv/bin/activate  # Activate the virtual environment
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser  # Create an admin user (optional)
python manage.py runserver

cd frontend
npm install
npm run dev

Configuration
Configure your Django project settings, such as database settings, secret key, and allowed hosts, in the backend/settings.py file.

For session-based authentication, ensure that Django's authentication settings are configured correctly, including the SESSION_COOKIE_SECURE setting for production.

Customize your authentication views, such as login and logout views, as needed in the backend/views.py file.

Usage
Access the Django admin interface at http://localhost:8000/admin/ to manage users and other data (if you created a superuser).
Visit the frontend application at http://localhost:3000/ to interact with the React-based user interface.
Contributing
Contributions are welcome! Please follow the guidelines outlined in CONTRIBUTING.md for reporting issues, suggesting improvements, and submitting pull requests.
