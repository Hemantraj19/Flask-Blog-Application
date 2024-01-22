# Flask Blog Application

A simple blog application built using Flask, SQLAlchemy, and other Flask extensions.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This Flask application provides a platform for creating and managing blog posts. Users can register, log in, create new posts, comment on posts, and perform other actions based on their roles. The application uses Flask-Login for user authentication and Flask-SQLAlchemy for database management.

## Features

- User registration and authentication
- Create, edit, and delete blog posts
- Comment on blog posts
- Admin-only features for post management
- Responsive design with Bootstrap

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flask-blog.git
   ```

2. Navigate to the project directory:
   ```bash
   cd flask-blog
   ```

3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On Unix or MacOS:
     ```bash
     source venv/bin/activate
     ```

5. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

6. Set up environment variables:
   - Create a `.env` file in the project root and add the following:
     ```env
     SECRET_KEY=your_secret_key
     DB_URI=your_database_uri
     ```

7. Initialize the database:
   ```bash
   python app.py
   ```

8. Run the application:
   ```bash
   python app.py
   ```

9. Access the application in your web browser at [http://localhost:5001/](http://localhost:5001/)

## Usage

- Visit the home page to view all blog posts.
- Register or log in to create new posts and comment on existing ones.
- Admin users (with ID 1) have additional privileges for post management.
- Explore different sections like About and Contact.

## Contributing

Feel free to contribute to the project.
