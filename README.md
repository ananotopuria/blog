# Django Blog Application

This is a fully functioning blog application built using Django. The app allows users to create blog posts, categorize them, and filter posts by category.

## Features

- **Create Blog Posts**: Add posts with a title, content, and category.
- **Category Filtering**: View posts based on their assigned category.
- **Date Tracking**: Automatically track when each post is created.

## Technologies Used

- **Python** (v3.12.5)
- **Django** (v4.1)
- **SQLite3** (default Django database)

## Project Structure

```bash
blog_project/
├── blog/               # Blog application directory
│   ├── migrations/     # Database migration files
│   ├── models.py       # Post model definition
│   ├── views.py        # Views to handle blog logic
│   ├── urls.py         # URL routing for blog app
│   └── templates/      # HTML templates for displaying blog posts
│       └── blog/       # Blog templates (list and detail views)
├── blog_project/       # Main Django project directory
│   ├── settings.py     # Project settings
│   ├── urls.py         # Main project URLs
│   ├── wsgi.py         # WSGI entry point for deployment
│   └── asgi.py         # ASGI entry point for async applications
└── manage.py           # Django management script
