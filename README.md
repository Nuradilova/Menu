# Menu

# Django Menu Backend Service

## Overview

This is a Django backend service for a restaurant menu management application. It provides APIs to manage dishes, orders, and media associated with various menu items.

## Features

- **Dish Management**: Create, retrieve, update, and delete dishes from the menu.
- **Order Processing**: Manage customer orders with CRUD operations.
- **Image Hosting**: Serve and manage images related to menu items.
- **Static Files**: Support for serving static files such as CSS, JavaScript, and images.
- **Test Coverage**: Comprehensive tests ensuring reliability and performance of order operations.

## Getting Started

### Prerequisites

- Python 3.8+
- pip
- Virtualenv (recommended)

### Installation

1. Clone the repository: git clone https://github.com/Nuradilova/Menu
2. Set up a virtual environment: python -m venv env and activate it
3. Install the dependencies: pip install -r requirements.txt
4. Apply the migrations: python manage.py migrate
5. Start the development server: python manage.py runserver
6. Visit localhost to see newly created app

## API Documentation

API endpoints are documented using Swagger/OpenAPI. After starting the server, you can visit `http://127.0.0.1:8000/swagger/` for interactive documentation and testing of the APIs.

## Testing

To run the tests, use the following command: python manage.py test

## Contributing

Please feel free to submit pull requests, open issues, or suggest new features.
