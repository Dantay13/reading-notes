# Class 1 Reading

## [Getting Started](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

- [How the Web Works.](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)
- [Website Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)
- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

1. Compose a short poem describing how HTTP sends data between computers.
<br> On a c

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
<br> The HTML file is parsed first, followed by the CSS style sheet, then lastly the javascript file.

3. How can you find images to add to a Website?
<br> You can find images to add to a website by going to Google Images and use the license filter to reduce the likelyhood of the images displayed are copyrighted.

4. How do you create a String vs a Number in JavaScript?
<br> In Javasceript to create a string data type, the value must be represented between single quotation marks `''` or double quotation marks `" "`. A number data type will only be represented by a numeral number.

5. What is a Variable and why are they important in JavaScript?
<br> Variables are containers that are given names and they store values that can be accesed by calling the variable. `let myVariable;`

## [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

- [Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- [HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
- [Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

1. What is an HTML attribute?
<br> HTML attributes are values (words) that are attached to elements in the opening tag that contain extra information about the element that won't appear in the content.

2. Describe the Anatomy of an HTMl element.
![HTML element anatomy](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png)

3. What is the Difference between `<article>` and `<section>` element tags?
<br> `<article>` encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).
<br> `<section>` is similar to `<article>`, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme. It's considered best practice to begin each section with a heading; also note that you can break `<article>`s up into different `<section>`s, or `<section>`s up into different `<article>`s, depending on the context.

4. What Elements does a “typical” website include?
<br> A typical webiste includes the following elemets: `<head>`, `<body>`, `<footer>`, `<nav>`, `<div>`, `<article>`, `<section>`, `<main>` and `<aside>`.

5. How does metadata influence Search Engine Optimization?
<br> Specifying a description that includes keywords relating to the content of your page has the potential to make your page appear higher in relevant searches performed in search engines (such activities are termed Search Engine Optimization, or SEO.).

6. How is the `<meta>` HTML tag used when specifying metadata?
<be> When specifying metadata, the `<meta>` tag is used and has attributes of either `name` or `property` to describe the content that will follow. The content attribute will then be the body of the information that will be displayed.

## Miscellaneous

1. What is the first step to designing a Website?
<br> Define what you want to accomplish with it.

2. What is the most important question to answer when designing a Website?
<br> What exactly do I want to accomplish?

### Semantics

1. Why should you use an `<h1>` element over a `<span>` element to display a top level heading?
<br> Because an `<h1>` element has sematic value that makes the font size larger and look like a heading. The `<span>` element has no semantic value so it will not have the same font as the `<h1>` by default.

2. What are the benefits of using semantic tags in our HTML?

- Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)
- Screen readers can use it as a signpost to help visually impaired users navigate a page
- Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes
- Suggests to the developer the type of data that will be populated
- Semantic naming mirrors proper custom element/component naming

### [What is Javascript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

1. Describe 2 things that require JavaScript in the Browser?

- event listeners
- Input and output information

2. How can you add JavaScript to an HTML document?
<br> You add Javascript to an HTML document with the external method which is: `<script>` tag. The tag should have the `href` attribute in it.


[<== BACK](README.md)