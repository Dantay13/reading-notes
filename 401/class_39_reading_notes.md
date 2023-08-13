# Class 39 Reading: React 3

## Reading

- [NextJs](https://nextjs.org/learn/basics/getting-started)
- [React Context for Beginners](https://www.freecodecamp.org/news/react-context-for-beginners/)

## Videos

- [Why I’m using Next.js in 2020](https://www.youtube.com/watch?v=rtgbaKBhdkk)
- [Learn useContext In 13 Minutes](https://www.youtube.com/watch?v=5LrDIWkK_Bc)

## Bookmark and Review

- [Next.js Examples](https://github.com/vercel/next.js/tree/canary/examples)

## Reading Questions

1. What is React Context, and how does it help in managing state and data sharing in a React application?

    React Context is a feature in React that enables the sharing of state and data across components without the need for prop drilling. It allows developers to create a context using the createContext method, provide values to components using a context provider, and consume those values in any component using a context consumer or the useContext hook. This facilitates global data sharing, making it easier to manage theme data, user information, or other global states. For example, by wrapping components in a UserContext.Provider and using React.useContext(UserContext), you can easily pass and access a user's name throughout the application.

2. Explain the useContext Hook and how it can be used to access data from a React Context within a functional component.

    The useContext Hook in React allows functional components to access the value of a context without complex nesting. By simply importing the Hook and passing the desired context to it, developers can retrieve the context value and use it within the component. In the video, this Hook is used to toggle between dark and light themes, demonstrating how useContext simplifies code by eliminating the need for consumer functions and nested structures, making it a more efficient and clean way to work with context in functional components.

3. Describe the purpose of Next.js, and provide an example from the Vercel Next.js Examples reading on how it can be used to build a scalable web application.

    Next.js is a React framework designed to simplify the development of scalable and performant web applications. It offers features like intuitive page-based routing, pre-rendering (both static and server-side), automatic code splitting, and built-in CSS support. An example from the Next.js Getting Started tutorial demonstrates how to create a simple blog app, showcasing how Next.js can be leveraged to build a web application that is both scalable and efficient, without the need for complex configurations or optimizations.
