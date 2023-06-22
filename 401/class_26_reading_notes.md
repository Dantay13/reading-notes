# Class 26 Reading: Intro to Django

## Reading 

- [Getting started with Django](https://www.djangoproject.com/start/)

- [How Django Works Behind the Scenes](https://wsvincent.com/how-django-works-behind-the-scenes/)

- [What is Tailwind CSS?](https://blog.hubspot.com/website/what-is-tailwind-css)

## Bookmark and Review

- [What is Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)
- [First Django App - Part 1](https://docs.djangoproject.com/en/4.1/intro/tutorial01/)
- [First Django App - Part 2](https://docs.djangoproject.com/en/4.1/intro/tutorial02/)
- [Tailwind CSS Django - Flowbite](https://flowbite.com/docs/getting-started/django/)

## Reading Questions

1. What are the key components of the Django framework, and how do they contribute to building a web application?

    The key components of the Django framework are:

    - Models: Define the data structures and handle interactions with the database.
    - Views: Handle the logic behind rendering web pages and processing user requests.
    - Templates: Generate the HTML content for web pages, incorporating data from views.
    - URLs: Map user-requested URLs to the corresponding views for processing.
    - Forms: Simplify user input handling and data validation.
    - Databases: Provide support for working with different database systems.

    These components work together to build web applications efficiently, with models managing data, views handling logic, templates creating HTML output, URLs mapping requests, forms simplifying user input, and databases facilitating database interactions.

2. Explain the role of Django’s MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle.

    Django's MTV (Model-View-Template) architecture separates the different aspects of a web application. During a typical web request-response cycle:

    - The Model retrieves or updates data from the database.
    - The View handles business logic and retrieves data from the Model.
    - The Template merges data with HTML structure to generate the HTML content.
    - The generated HTML is sent back as the response to the user's request.

    MTV ensures separation of concerns, improving modularity and maintainability of the application. Models handle data and database interactions, Views handle logic and data processing, and Templates handle HTML rendering.

3. What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?

    Tailwind CSS is a type of CSS framework that makes it easier to create user interfaces by providing ready-to-use CSS classes with specific purposes. It is different from Bootstrap CSS because it focuses more on customization and flexibility, which means you can adjust and change things more easily. However, this may make the initial file size bigger, although you can remove unused CSS to make it smaller. Tailwind CSS lets you design things without any specific style in mind, while Bootstrap CSS comes with a set look and feel.