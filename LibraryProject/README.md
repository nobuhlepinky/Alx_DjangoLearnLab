# LibraryProject

## Overview

LibraryProject is a Django application designed to manage a library system. It provides functionality for managing books, users, and borrowing records.

## Features

- Book management (add, update, delete books)
- User authentication and management
- Borrowing and return tracking
- Book availability status

## Installation

1. Navigate to the LibraryProject directory
2. Install dependencies: pip install -r requirements.txt
3. Run migrations: python manage.py migrate
4. Start the development server: python manage.py runserver

## Project Structure

- manage.py - Django management script
- LibraryProject/ - Main project configuration directory
  - settings.py - Django settings
  - urls.py - URL routing
  - wsgi.py - WSGI configuration
  - sgi.py - ASGI configuration

## Usage

Start the development server and navigate to http://localhost:8000/ to access the application.

## Database

The project uses SQLite for development. The database file is db.sqlite3.

## Contributing

Please follow Django best practices and ensure all tests pass before submitting changes.
