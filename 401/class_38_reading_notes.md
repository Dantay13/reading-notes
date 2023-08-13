# Class 38 Readings: React 2

## Reading

[React - Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)
[React - Lists & Keys](https://reactjs.org/docs/lists-and-keys.html)
[React - Forms](https://reactjs.org/docs/forms.html)
[React - Lifting State](https://reactjs.org/docs/lifting-state-up.html)
[React - Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)
[https://reactjs.org/docs/thinking-in-react.html](https://reactjs.org/docs/thinking-in-react.html)

## Bookmark and Review

[React - Comprehensive Guide](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/)
[Heroicons](https://heroicons.com/)

## Reading Questions

1. How does lifting state up in a React application help with managing data flow and what are the benefits of using this approach?

    Lifting state up in a React application refers to moving shared state to a common ancestor component, serving as a single source of truth for data that changes. By controlling the state from a parent component, it keeps the inputs in sync, simplifies debugging, avoids two-way binding complexities, and allows for custom logic to handle user input. It promotes a clear and efficient top-down data flow, enhancing the consistency and flexibility of the application.

2. Explain the concept of conditional rendering in React and provide an example of how to implement it in a component.

    Conditional rendering in React allows developers to render different components or elements based on specific conditions or states. It utilizes JavaScript operators like if or the conditional operator to dynamically create elements.

3. What are the main principles behind “Thinking in React” and how do they guide the process of designing and building a React application?

    "Thinking in React" is a methodology for building React applications that emphasizes a component-based architecture. It involves breaking the UI into a hierarchy of components, building a static version without interactivity, identifying the minimal UI state, determining where the state should live, and adding inverse data flow.
