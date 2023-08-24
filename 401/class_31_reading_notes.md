# Readings: Django REST Framework & Docker

## Reading

[Beginner’s Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)
[Django for APIs - Library Website](https://djangoforapis.com/library-website-and-api/)

## Bookmark and Review

[Beginner’s Guide to Django REST Framework](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)

## Reading Questions

1. What are the key components of a Docker container, and how do they help streamline the development and deployment of applications?

    Docker is a platform that enables developers to package applications and their dependencies into isolated containers. Containers provide a consistent environment for an application to run in, regardless of the underlying infrastructure.

    1. Image
    2. Container
    3. Docker Engine
    4. Dockerfile
    5. Docker Compose
    6. Docker Registry

2. Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.

    - Create a new Django project using the django-admin startproject command.
    - Create a new Django app using the python manage.py startapp command.
    - Define Django models that represent the main data entities of the library.
    - Define fields for each model class, specifying data types like CharField, IntegerField, ForeignKey, etc.
    - Configure the database settings in the project's settings.py file.
    - Generate and apply migrations to create the database schema based on the defined models. Use the python manage.py makemigrations and python manage.py migrate commands.
    - Register the models with the Django admin interface to allow easy management of data through a web-based administration panel.
    - Customize the admin panel by creating admin classes that define the displayed fields, filters, and search options.
    - Define views (functions or classes) in the app's views.py file.
    - Create URL patterns in the app's urls.py file, mapping URLs to specific views using regular expressions.
    - Create HTML templates that define the structure and layout of the web pages.
    - Organize templates in a dedicated directory structure, typically within the app's "templates" folder.
    - Store static files like CSS, JavaScript, and images in a "static" directory within the app.
    - Configure the project's settings to serve static files during development.
    - Implement the logic for views, fetching data from the database using models and passing it to templates.
    - In views, render templates using the render function and pass data as context.
    - Create navigation links and URLs in templates using the template tag, which references the URL patterns defined in the app's urls.py.

3. Can you explain the primary differences between Django and Django REST framework?

    In summary, the primary difference between Django and Django REST framework lies in their focus and purpose. Django is a full-stack web framework for building complete web applications with user interfaces, while Django REST framework is an extension of Django specifically tailored for building APIs that facilitate data exchange between different applications or services.
