# Class 41 Readings: React 4

## Readings

[Next.js - Dynamic Routes](https://nextjs.org/learn/basics/dynamic-routes)
[Next.js - Deployment](https://nextjs.org/learn/basics/deploying-nextjs-app)

## Videos

[Next.js 10 is here](https://www.youtube.com/watch?v=JWCS5IdECVI)

## Bookmark and Review

[Next.js - Static File Serving](https://nextjs.org/docs/basic-features/static-file-servingc)

## Reading Questions

1. Explain the concept of dynamic routes in Next.js and how they differ from static routes.

    Dynamic routes in Next.js allow you to create pages with URLs based on dynamic data, enabling content to change based on parameters in the URL, while static routes have fixed content and URLs mapped to physical files. Dynamic routes generate content at runtime, handling various data scenarios without the need for separate static files for each case, making it ideal for data-driven pages.

2. Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?

    1. Build the Next.js Application
    2. Choose a Hosting Platform:
        - Vercel
        - Netlify
        - AWS Amplify
        - Heroku
        - DigitalOcean
    3. Deploy the Application
    4. Configure DNS and Domain
    5. Monitor and Scale

3. How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.

    Next.js handles static file serving through the "public" directory, serving static assets like images, stylesheets, and client-side JavaScript directly to the client without an additional server. To reference static assets in a Next.js application, use standard HTML tags (e.g., img, link, script) with the relative URL path of the asset within the "public" folder. Next.js automatically optimizes served static assets with caching and compression headers, improving performance. Note that files outside "public" are not accessible by default, and custom API routes are required to serve them.
