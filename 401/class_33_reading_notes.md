# Class 33 Readings: Authentication & Production Server

## Reading

[JSON Web Tokens](https://jwt.io/introduction/)
[DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
[Django Runserver Is Not Your Production Server White Noise](https://build.vsupalov.com/django-runserver-in-production/)

## Videos

[JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)

## Bookmark and Review

[Gunicorn](https://gunicorn.org/)

## Reading Questions

1. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

    The primary purpose of JWTs is to securely transmit information between parties, typically a client (such as a user's browser) and a server. JWTs are often used for implementing Single Sign-On (SSO) functionality, where a user logs in once and gains access to multiple resources or services without needing to log in again for each one.

    - Header: The header typically consists of two parts: the type of the token (JWT) and the signing algorithm being used (e.g., HMAC SHA256 or RSA). This header is then Base64Url encoded to form the first part of the JWT.

    - Payload: The payload contains the claims. Claims are statements about an entity (typically, the user) and additional data. There are three types of claims: registered, public, and private claims. The payload is also Base64Url encoded to form the second part of the JWT.

    - Signature: To create the signature part, you take the encoded header, encoded payload, a secret (or a public/private key pair), and the algorithm specified in the header, and then you sign that data. The signature helps verify that the sender of the JWT is who it says it is and that the message wasn't changed along the way.

2. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

    - Authentication Backend:
    - Authentication Views
    - Settings Configuration
    - Token Generation
    - Token Storage
    - Sending Tokens with Requests
    - Token Validation
    - Customization

3. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

    Django's built-in runserver is unsuitable for production due to limited performance, security, and configuration, while alternatives like Gunicorn, uWSGI, nginx, and Docker/Kubernetes provide better scalability and features.
