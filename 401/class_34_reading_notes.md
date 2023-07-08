# Readings: API Deployment

## Reading

- [Django Settings Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)

## Bookmark and Review

- [White Noise](http://whitenoise.evans.io/en/stable/)
- [CORS](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)

## Reading Questions

1. What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?

    - Separate settings: Divide settings into multiple files for better organization.
    - Environment-specific settings: Use different settings files for different environments.
    - Secure and version-controlled approach: Avoid storing sensitive information directly in settings files and use environment variables or external files instead.
    - Follow the 12-factor app methodology: Adhere to principles like storing configuration in the environment and treating services as attached resources.
    - Separate secret settings: Store sensitive information separately from other settings.
    - Use relative paths: Specify file paths using relative paths for better portability.
    - Organize with modules: Split settings into modules based on functionality.
    - Utilize Django's built-in mechanisms: Take advantage of Django's built-in configuration mechanisms and libraries like django-environ.

2. How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?

    White Noise is a library for efficiently serving static files in Django applications. It helps improve performance and simplifies the serving of static assets.

    1. Install White Noise: Add White Noise to your project's dependencies by installing it using pip: `pip install whitenoise`.
    2. Configure middleware: In your Django project's settings, add the White Noise middleware to the `MIDDLEWARE` list. Place it after Django's `SecurityMiddleware` and before any other middleware that may modify the response.

        ```py
        MIDDLEWARE = [
            # ...
            'django.middleware.security.SecurityMiddleware',
            'whitenoise.middleware.WhiteNoiseMiddleware',
            # ...
        ]
        ```

    3. Configure static files storage: Update your Django project's `STATICFILES_STORAGE` setting to use White Noise's `WhiteNoise` class.

        ```py
        STATICFILES_STORAGE = 'whitenoise.storage.CompressedManifestStaticFilesStorage'
        ```

    4. Collect static files: Run the `collectstatic` management command to gather your project's static files into a single location.

    ```py
    python manage.py collectstatic
    ```

    5. Configure web server: If you're using a web server like Nginx or Apache, configure it to serve the static files directly. Make sure to disable any configuration related to serving static files by the web server.
    In development, you can run your Django application with the White Noise middleware serving the static files directly without needing a separate web server.

3. What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?

    Cross-Origin Resource Sharing (CORS) is a mechanism that allows web browsers to securely access resources (such as fonts, images, scripts, or APIs) on a different domain than the one from which the web page originated. Its purpose is to enforce browser-side security and protect against cross-site scripting (XSS) and cross-site request forgery (CSRF) attacks.

    1. Install Django CORS headers
    2. Add the CORS middleware
    3. Configure allowed origins
    4. Configure other CORS options
    5. Testing and production configuration
